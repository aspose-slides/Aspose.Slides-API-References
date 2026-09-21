---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.importing/externalresourceresolver/
---
## ExternalResourceResolver 類別

用於在 Html、Svg 文件匯入期間解析外部資源的回呼類別。使用此解析器可能會產生安全漏洞，當客戶端提供的 HTML 或 SVG 檔案使伺服器軟體取得本機或網路檔案時。請謹慎使用。建議完全不指定 ExternalResourceResolver（僅會讀取嵌入的物件），或建立子類別以檢查指定的 uri 是否有效。

ExternalResourceResolver 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/zh-hant/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | 從基礎 URI 和相對 URI 解析絕對 URI。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/zh-hant/aspose.slides.importing/externalresourceresolver/get_entity/#str) | 將 URI 對映至包含實際資源的物件。 |


### 另請參閱
* 模組 [`aspose.slides.importing`](/slides/python-net/zh-hant/aspose.slides.importing)
* 函式庫 [`Aspose.Slides`](/slides/python-net)