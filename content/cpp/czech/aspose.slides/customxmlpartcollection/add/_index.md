---
title: Add()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá novou vlastní XML část.
type: docs
weight: 53
url: /cs/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) metoda

Přidá novou vlastní XML část.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | Řetězec XML nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní XML část.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) metoda

Přidá novou vlastní XML část.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Data XML nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní XML část.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) metoda

Přidá novou vlastní XML část.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Vstupní proud inputStream s XML daty nové části, která má být přidána. |

### Návratová hodnota

Vytvořená vlastní XML část.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICustomXmlPart](../../icustomxmlpart/)
* Třída [String](../../../system/string/)
* Třída [CustomXmlPartCollection](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)