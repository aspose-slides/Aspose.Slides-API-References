---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds new custom xml part.
type: docs
weight: 14
url: /aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) method


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The xml data of new part to be added. |

### Return Value

Created custom xml part.

## ICustomXmlPartCollection::Add(System::String) method


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | The xml string of new part to be added. |

### Return Value

Created custom xml part.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) method


Adds new custom xml part.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The inputStream with xml data of new part to be added. |

### Return Value

Created custom xml part.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICustomXmlPart](../../icustomxmlpart/)
* Class [ICustomXmlPartCollection](../)
* Class [String](../../../system/string/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)