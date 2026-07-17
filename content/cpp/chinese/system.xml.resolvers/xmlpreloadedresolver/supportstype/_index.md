---
title: SupportsType()
second_title: Aspose.Slides C++ API 参考
description: 确定解析器是否支持除 Stream 之外的其他 Types。
type: docs
weight: 66
url: /zh/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) 方法


确定解析器是否支持除 Stream 之外的其他 Types。

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 要检查的绝对 URI。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的 Type。 |

### 返回值

**true** if the Type is supported; otherwise, **false**.

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)