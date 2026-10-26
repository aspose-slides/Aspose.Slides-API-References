---
title: GetEntity()
second_title: Aspose.Slides C++ API 参考
description: 在派生类中重写时，将 URI 映射到包含实际资源的对象。
type: docs
weight: 14
url: /zh/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

在派生类中重写时，将 URI 映射到包含实际资源的对象。

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 从 [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 调用返回的 URI。 |
| role | [String](../../../system/string/) | 当前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的对象类型。目前版本仅返回 Stream 对象。 |

### 返回值

如果指定的类型为流，则返回 Stream 对象；否则返回 **nullptr**。

## 另请参见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)