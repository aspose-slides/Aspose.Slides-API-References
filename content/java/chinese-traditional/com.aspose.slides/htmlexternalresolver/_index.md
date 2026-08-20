---
title: HtmlExternalResolver
second_title: Aspose.Slides for Java API 參考
description: HTML 匯入例程使用的回呼物件，用於取得參考的物件，例如圖像。
type: docs
url: /zh-hant/com.aspose.slides/htmlexternalresolver/
---
**繼承:**
java.lang.Object

**全部實作的介面:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML 匯入例程使用的回呼物件，用於取得參考的物件，例如圖像。

--------------------

使用此解析器可能會產生漏洞，因為客戶端提供的 HTML 檔案可能會使伺服器軟體取得本機或網路檔案。請謹慎使用。建議不指定 HtmlExternalResolver（僅會讀取內嵌物件），或自行建立子類別以檢查指定的 uri 是否有效。
## 建構函式

| Constructor | Description |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## 方法

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


解析基礎 URI 與相對 URI 以取得絕對 URI。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | 連結物件的基礎 URI |
| relativeUri | java.lang.String | 連結至該物件的相對 URI。 |

**傳回值:**
java.lang.String - 絕對 URI，若無法解析相對 URI 則為 null。
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


將 URI 對映至包含實際資源的物件。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | 指向該物件的絕對 URI。 |

**傳回值:**
java.io.InputStream - InputStream 物件，若資源無法串流則為 null。