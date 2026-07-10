---
title: ExternalResourceResolver
second_title: Aspose.Slides for Android via Java API 参考
description: 用于在 Html、Svg 文档导入期间解析外部资源的回调类。
type: docs
url: /zh/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

用于在 Html、Svg 文档导入期间解析外部资源的回调类。

--------------------

使用此解析器可能会导致漏洞，当客户端提供的 HTML 或 SVG 文件使服务器软件获取本地或网络文件时。请谨慎使用。建议不要指定 ExternalResourceResolver（仅读取嵌入对象），或创建子类以检查指定的 uri 是否有效。

## 构造函数

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## 方法

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 从基准 URI 和相对 URI 解析出绝对 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 将 URI 映射到包含实际资源的对象。 |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

从基准 URI 和相对 URI 解析出绝对 URI。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | 链接对象的基准 URI |
| relativeUri | java.lang.String | 链接对象的相对 URI |

**Returns:**
java.lang.String - 绝对 URI；如果无法解析相对 URI 则返回 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

将 URI 映射到包含实际资源的对象。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | 对象的绝对 URI。 |

**Returns:**
java.io.InputStream - 一个 InputStream 对象；如果资源无法流式传输则返回 null。