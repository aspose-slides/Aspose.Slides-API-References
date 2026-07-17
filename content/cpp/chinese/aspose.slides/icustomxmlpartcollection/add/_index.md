---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 添加新的自定义 xml 部分。
type: docs
weight: 14
url: /zh/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 方法

添加新的自定义 XML 部分。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要添加的新部分的 XML 数据。 |

### 返回值

已创建的自定义 XML 部分。

## ICustomXmlPartCollection::Add(System::String) 方法

添加新的自定义 XML 部分。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 要添加的新部分的 XML 字符串。 |

### 返回值

已创建的自定义 XML 部分。

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 方法

添加新的自定义 XML 部分。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要添加的新部分的 XML 数据输入流。 |

### 返回值

已创建的自定义 XML 部分。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [ICustomXmlPart](../../icustomxmlpart/)
* 类 [ICustomXmlPartCollection](../)
* 类 [String](../../../system/string/)
* 类 [Stream](../../../system.io/stream/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)