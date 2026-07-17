---
title: GetEntity()
second_title: Aspose.Slides C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 27
url: /zh/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

将 URI 映射到包含实际资源的对象。

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 从 [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 调用返回的 URI。 |
| role | [String](../../../system/string/) | 当前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的对象类型。当前版本仅返回 Stream 对象。 |

### 返回值

在底层 [XmlResolver](../../xmlresolver/) 上调用 **GetEntity** 返回的流。如果指定的类型不是 Stream，方法返回 **nullptr**。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlSecureResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)