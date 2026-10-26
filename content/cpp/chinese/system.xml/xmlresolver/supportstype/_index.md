---
title: SupportsType()
second_title: Aspose.Slides for C++ API 参考
description: 启用解析器返回除 Stream 之外的类型。
type: docs
weight: 40
url: /zh/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) 方法


启用解析器返回除 Stream 之外的类型。

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI。 |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 要返回的类型。 |

### 返回值

**true** if the **type** is supported; otherwise, **false**.

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Uri](../../../system/uri/)
* 类 [TypeInfo](../../../system/typeinfo/)
* 类 [XmlResolver](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)