---
title: HtmlExternalResolver
second_title: Aspose.Slides for Android 透過 Java API 參考
description: HTML 匯入例程使用的回呼物件，用於取得參考的物件，例如圖像。
type: docs
url: /zh-hant/com.aspose.slides/htmlexternalresolver/
---
**繼承:**  
java.lang.Object

**已實作的介面:**  
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)  
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

回呼物件用於 HTML 匯入例程以取得參考的物件，例如圖像。

--------------------

使用此解析器可能會產生漏洞，當客戶端提供的 HTML 檔案使伺服器軟體取得本機或網路檔案時。請謹慎使用。建議完全不要指定 HtmlExternalResolver（只會讀取嵌入式物件），或建立檢查指定 URI 是否有效的子類別。

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## 方法

| 方法 | 說明 |
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

從基礎與相對 URI 解析出絕對 URI。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | java.lang.String | 連結物件的基礎 URI |
| relativeUri | java.lang.String | 連結物件的相對 URI。 |

**返回值:**
java.lang.String - 絕對 URI，若無法解析相對 URI 則返回 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

將 URI 對映至包含實際資源的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 指向該物件的絕對 URI。 |

**返回值:**
java.io.InputStream - InputStream 物件，若資源無法串流則返回 null。