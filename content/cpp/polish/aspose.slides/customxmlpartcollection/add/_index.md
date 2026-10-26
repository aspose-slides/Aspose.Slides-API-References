---
title: Add()
second_title: Aspose.Slides - dokumentacja API dla C++
description: Dodaje nową niestandardową część XML.
type: docs
weight: 53
url: /pl/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) metoda


Dodaje nową część XML.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | Ciąg XML nowej części, która ma zostać dodana. |

### Wartość zwracana

Utworzona część XML.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) metoda


Dodaje nową część XML.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dane XML nowej części, która ma zostać dodana. |

### Wartość zwracana

Utworzona część XML.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) metoda


Dodaje nową część XML.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień wejściowy z danymi XML nowej części, która ma zostać dodana. |

### Wartość zwracana

Utworzona część XML.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICustomXmlPart](../../icustomxmlpart/)
* Klasa [String](../../../system/string/)
* Klasa [CustomXmlPartCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)