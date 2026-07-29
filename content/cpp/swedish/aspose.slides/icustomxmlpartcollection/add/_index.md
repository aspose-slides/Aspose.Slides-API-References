---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny anpassad xml-del.
type: docs
weight: 14
url: /sv/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) metod

Lägger till ny anpassad xml del.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | XML data för den nya delen som ska läggas till. |

### Returvärde

Skapad anpassad xml del.

## ICustomXmlPartCollection::Add(System::String) metod

Lägger till ny anpassad xml del.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | XML-strängen för den nya delen som ska läggas till. |

### Returvärde

Skapad anpassad xml del.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) metod

Lägger till ny anpassad xml del.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | inputStream med xml data för den nya delen som ska läggas till. |

### Returvärde

Skapad anpassad xml del.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICustomXmlPart](../../icustomxmlpart/)
* Klass [ICustomXmlPartCollection](../)
* Klass [String](../../../system/string/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)