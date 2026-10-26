---
title: ExternalResourceResolver
second_title: Aspose.Slides for Java API 参考
description: 在 Html、Svg 文档导入期间用于解析外部资源的回调类。
type: docs
url: /zh/com.aspose.slides/externalresourceresolver/
---
**继承:**  
java.lang.Object

**全部已实现接口:**  
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)  
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

在 Html、Svg 文档导入期间用于解析外部资源的回调类。

--------------------

使用此解析器可能会产生漏洞，当客户端提供的 HTML 或 SVG 文件导致服务器软件获取本地或网络文件时。请谨慎使用。建议根本不要指定 ExternalResourceResolver（仅读取嵌入的对象），或创建检查指定 uri 是否有效的子类。

## 构造函数

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## 方法

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

解析基 URI 和相对 URI 的绝对 URI。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | 链接对象的基 URI |
| relativeUri | java.lang.String | 相对 URI，指向链接对象的 URI |

**返回值:**
java.lang.String - 绝对 URI，或者如果无法解析相对 URI 则返回 null。

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

将 URI 映射到包含实际资源的对象。

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | 对象的绝对 URI |

**返回值:**
java.io.InputStream - 一个 InputStream 对象，若资源无法流式传输则返回 null。