---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá novou vlastní část XML.
type: docs
weight: 14
url: /cs/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) metoda

Přidá novou vlastní část XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | XML data nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní část XML.

## ICustomXmlPartCollection::Add(System::String) metoda

Přidá novou vlastní část XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | XML řetězec nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní část XML.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) metoda

Přidá novou vlastní část XML.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud s XML daty nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní část XML.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICustomXmlPart](../../icustomxmlpart/)
* Třída [ICustomXmlPartCollection](../)
* Třída [String](../../../system/string/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)