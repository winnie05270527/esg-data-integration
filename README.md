
# ESG 公開資訊整合平台

## 概要

ESG 公開資訊整合平台是一個專案，旨在建立一個自動化的數據整合和監控系統，利用ELK工具（Elasticsearch, Logstash, Kibana）來實現即時監控、數據抓取、轉換與預處理，以及數據集中儲存，提供可靠的基礎。

## 專案目標

我們的主要目標是建立一個資料整合平台，能夠自動地獲取、整理和監控政府開放數據，以支持環境、社會和治理（ESG）數據的收集和分析。具體來說，專案的核心工作包括：

1.**政府API數據抓取：** 我們使用Python程式自動從政府提供的各種API中獲取相關數據，包括天氣、氣候、交通和其他重要資訊。

2.**數據轉換和預處理：** 我們確保從API中獲取的數據格式符合我們的需求，進行數據轉換、清理和處理，以確保數據的質量和一致性。

3.**數據集中儲存：** 所有抓取的數據都被集中儲存，以便後續的分析和查詢。

4.**ELK工具的使用：** 我們使用Elasticsearch、Logstash和Kibana（ELK）工具來建立一個實時監控和分析平台，使我們能夠即時檢視數據、生成報告和識別趨勢。
