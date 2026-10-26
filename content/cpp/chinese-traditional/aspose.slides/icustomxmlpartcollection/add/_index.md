---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 新增自訂 XML 部件。
type: docs
weight: 14
url: /zh-hant/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 方法

新增自訂 XML 部件。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要新增之部件的 XML 資料。 |

### 返回值

已建立自訂 XML 部件。

## ICustomXmlPartCollection::Add(System::String) 方法

新增自訂 XML 部件。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 要新增之部件的 XML 字串。 |

### 返回值

已建立自訂 XML 部件。

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 方法

新增自訂 XML 部件。

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含新部件 XML 資料的輸入串流。 |

### 返回值

已建立自訂 XML 部件。

## 另見

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICustomXmlPart](../../icustomxmlpart/)
* 類別 [ICustomXmlPartCollection](../)
* 類別 [String](../../../system/string/)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)