---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: 用于在导入 Html、Svg 文档期间解析外部资源的回调接口。
type: docs
url: /zh/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

用于在导入 Html、Svg 文档期间解析外部资源的回调接口。

## 方法

| 方法 | 描述 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

解析基 URI 和相对 URI 以得到绝对 URI。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**返回值：**
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

将 URI 映射到包含实际资源的对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**返回值：**
java.io.InputStream - A InputStream object or null if resource cannot be streamed.