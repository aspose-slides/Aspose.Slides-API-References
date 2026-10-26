---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 添加新的自定义 XML 部分。
type: docs
weight: 53
url: /zh/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) 方法

添加新的自定义 XML 部分。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 要添加的新部分的 xml 字符串。 |

### 返回值

已创建自定义 XML 部分。

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 方法

添加新的自定义 XML 部分。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要添加的新部分的 xml 数据。 |

### 返回值

已创建自定义 XML 部分。

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 方法

添加新的自定义 XML 部分。

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含要添加的新部分 xml 数据的 inputStream。 |

### 返回值

已创建自定义 XML 部分。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICustomXmlPart](../../icustomxmlpart/)
* 类 [String](../../../system/string/)
* 类 [CustomXmlPartCollection](../)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)