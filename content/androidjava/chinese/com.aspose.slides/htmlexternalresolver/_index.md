---
title: HtmlExternalResolver
second_title: Aspose.Slides for Android via Java API 参考
description: HTML 导入例程使用的回调对象，用于获取诸如图像等引用对象。
type: docs
url: /zh/com.aspose.slides/htmlexternalresolver/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

HTML 导入例程使用的回调对象，用于获取诸如图像之类的引用对象。

--------------------

使用此解析器可能会导致漏洞，当客户端提供的 HTML 文件使服务器软件获取本地或网络文件时。请谨慎使用。建议完全不指定 HtmlExternalResolver（仅读取嵌入的对象），或创建一个子类来检查指定的 uri 是否有效。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | 解析基准和相对 URI 以获得绝对 URI。 |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | 将 URI 映射到包含实际资源的对象。 |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

解析基准和相对 URI 以获得绝对 URI。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | java.lang.String | 链接对象的基准 URI |
| relativeUri | java.lang.String | 链接对象的相对 URI。 |

**返回值：**
java.lang.String - 绝对 URI，若相对 URI 无法解析则返回 null。
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

将 URI 映射到包含实际资源的对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | java.lang.String | 对象的绝对 URI。 |

**返回值：**
java.io.InputStream - 一个 InputStream 对象，若资源无法流式传输则返回 null。