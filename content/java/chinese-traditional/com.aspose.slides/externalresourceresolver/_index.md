---
title: ExternalResourceResolver
second_title: Aspose.Slides for Java API 參考
description: 在 Html、Svg 文件匯入期間，用於解析外部資源的回呼類別。
type: docs
url: /zh-hant/com.aspose.slides/externalresourceresolver/
---
**繼承:**  
java.lang.Object

**全部已實作的介面:**  
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)  
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

在 Html、Svg 文件匯入期間，用於解析外部資源的回呼類別。

--------------------

使用此解析器可能會產生漏洞，因為客戶端提供的 HTML 或 SVG 檔案會使伺服器軟體取得本機或網路檔案。請謹慎使用。建議完全不要指定 ExternalResourceResolver（僅會讀取內嵌物件），或自行建立子類別以檢查指定的 uri 是否有效。

## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 解析基礎 URI 與相對 URI 合成的絕對 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 將 URI 對映至包含實際資源的物件。 |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

解析基礎 URI 與相對 URI 合成的絕對 URI。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| baseUri | java.lang.String | 連結物件的基礎 URI |
| relativeUri | java.lang.String | 相對於已連結物件的 URI |

**返回值:**
java.lang.String - 若無法解析相對 URI，則返回絕對 URI 或 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

將 URI 對映至包含實際資源的物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 指向該物件的絕對 URI |

**返回值:**
java.io.InputStream - 若資源無法串流，則返回 InputStream 物件或 null。