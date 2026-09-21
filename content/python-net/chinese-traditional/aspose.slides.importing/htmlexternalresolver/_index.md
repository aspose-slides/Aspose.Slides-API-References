---
title: HtmlExternalResolver class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.importing/htmlexternalresolver/
---
## HtmlExternalResolver 類別

此回呼物件用於 HTML 匯入程序，以取得諸如圖像等參考的物件。  
使用此解析器可能會造成安全漏洞，因為客戶端提供的 HTML 檔案可能使伺服器軟體取得本機或網路上的檔案。請謹慎使用。建議完全不指定 HtmlExternalResolver（僅會讀取內嵌物件），或自行建立子類別，於其中檢查指定的 uri 是否有效。

HtmlExternalResolver 類型提供以下成員：

## 建構子

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides.importing/htmlexternalresolver/__init__/#) |  |

## 方法

| Method | Description |
| :- | :- |
| [`resolve_uri(self, base_uri, relative_uri)`](/slides/python-net/zh-hant/aspose.slides.importing/htmlexternalresolver/resolve_uri/#str-str) | 從基礎 URI 與相對 URI 解析出絕對 URI。 |
| [`get_entity(self, absolute_uri)`](/slides/python-net/zh-hant/aspose.slides.importing/htmlexternalresolver/get_entity/#str) | 將 URI 對應至包含實際資源的物件。 |


### 另請參閱
* 模組 [`aspose.slides.importing`](/slides/python-net/zh-hant/aspose.slides.importing)
* 函式庫 [`Aspose.Slides`](/slides/python-net)