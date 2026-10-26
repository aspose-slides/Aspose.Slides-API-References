---
title: GetEntity()
second_title: Aspose.Slides for C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 53
url: /zh/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

将 URI 映射到包含实际资源的对象。

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 从 [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) 调用返回的 URI。 |
| role | [String](../../../system/string/) | 当前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的对象类型。当前实现仅返回 Stream 对象。 |

### 返回值

如果指定的类型不是 stream，则返回 stream 对象或 **nullptr**。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlUrlResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)