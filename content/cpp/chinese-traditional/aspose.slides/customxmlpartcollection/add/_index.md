---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 新增自訂 xml 部件。
type: docs
weight: 53
url: /zh-hant/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) 方法


Adds new custom xml part.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | 要加入的新部件的 xml 字串。 |

### 傳回值

已建立的自訂 XML 部件。

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) 方法


Adds new custom xml part.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要加入的新部件的 xml 資料。 |

### 傳回值

已建立的自訂 XML 部件。

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) 方法


Adds new custom xml part.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要加入的新部件的 xml 資料的 inputStream。 |

### 傳回值

已建立的自訂 XML 部件。

## See Also

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICustomXmlPart](../../icustomxmlpart/)
* 類別 [String](../../../system/string/)
* 類別 [CustomXmlPartCollection](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)