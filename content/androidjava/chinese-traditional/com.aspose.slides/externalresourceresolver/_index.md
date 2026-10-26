---
title: ExternalResourceResolver
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 在 Html、Svg 文件匯入期間用於解析外部資源的回呼類別。
type: docs
url: /zh-hant/com.aspose.slides/externalresourceresolver/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

用於在 Html、Svg 文件匯入期間解析外部資源的回呼類別。

--------------------

使用此解析器可能會在客戶端提供的 HTML 或 SVG 檔案使伺服器軟體取得本機或網路檔案時產生漏洞。請小心使用。建議根本不要指定 ExternalResourceResolver（僅會讀取嵌入式物件），或建立檢查指定 uri 是否有效的子類別。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 解析自基礎 URI 與相對 URI 的絕對 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 將 URI 映射到包含實際資源的物件。 |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

解析自基礎 URI 與相對 URI 的絕對 URI。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | java.lang.String | 連結物件的基礎 URI |
| relativeUri | java.lang.String | 連結物件的相對 URI。 |

**回傳值:**
java.lang.String - 絕對 URI，若無法解析相對 URI 則回傳 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

將 URI 映射到包含實際資源的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 物件的絕對 URI。 |

**回傳值:**
java.io.InputStream - InputStream 物件，若資源無法串流則回傳 null。