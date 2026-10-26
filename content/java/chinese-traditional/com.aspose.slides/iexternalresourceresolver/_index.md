---
title: IExternalResourceResolver
second_title: Aspose.Slides 的 Java API 參考
description: 在 Html、Svg 文件匯入期間用於解析外部資源的回呼介面。
type: docs
url: /zh-hant/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

在 Html、Svg 文件匯入期間用於解析外部資源的回呼介面。

## 方法

| 方法 | 說明 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 解析來自基礎 URI 與相對 URI 的絕對 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 將 URI 映射到包含實際資源的物件。 |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


解析來自基礎 URI 與相對 URI 的絕對 URI。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| baseUri | java.lang.String | 連結物件的基礎 URI |
| relativeUri | java.lang.String | 連結物件的相對 URI。 |

**傳回:**
java.lang.String - 絕對 URI，或如果相對 URI 無法解析則返回 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```


將 URI 映射到包含實際資源的物件。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 物件的絕對 URI。 |

**傳回:**
java.io.InputStream - InputStream 物件，或如果資源無法串流則返回 null。