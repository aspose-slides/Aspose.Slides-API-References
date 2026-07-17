---
title: GetEntity()
second_title: Aspose.Slides for C++ API 参考
description: 将 URI 映射到包含实际资源的对象。
type: docs
weight: 53
url: /zh/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 方法

将 URI 映射到包含实际资源的对象。

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 从 [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) 调用返回的 URI。 |
| role | [String](../../../system/string/) | 当前未使用。 |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 返回对象的类型。[XmlPreloadedResolver](../) 支持用于作为 [String](../../../system/string/) 添加的 URI 的 Stream 对象和 TextReader 对象。如果解析器不支持请求的类型，将抛出异常。使用 XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) 方法来确定解析器是否支持特定的 **Type**。 |

### 返回值

对应实际来源的 Stream 或 TextReader 对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [Uri](../../../system/uri/)
* 类 [String](../../../system/string/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlPreloadedResolver](../)
* 命名空间 [System::Xml::Resolvers](../../)
* 库 [Aspose.Slides](../../../)