---
title: IExternalResourceResolver
second_title: Aspose.Slides 的 Java API 参考
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
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 解析基准 URI 与相对 URI 合成的绝对 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 将 URI 映射到包含实际资源的对象。 |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

解析基准 URI 与相对 URI 合成的绝对 URI。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | java.lang.String | 链接对象的基准 URI |
| relativeUri | java.lang.String | 链接对象的相对 URI |

**返回值:**
java.lang.String - 绝对 URI，如果相对 URI 无法解析则返回 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

将 URI 映射到包含实际资源的对象。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 对象的绝对 URI。 |

**返回值:**
java.io.InputStream - InputStream 对象，如果资源无法流式传输则返回 null。