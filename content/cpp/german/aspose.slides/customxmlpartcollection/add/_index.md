---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen benutzerdefinierten XML-Teil hinzu.
type: docs
weight: 53
url: /de/aspose.slides/customxmlpartcollection/add/
---
## CustomXmlPartCollection::Add(System::String) Methode


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::String xmlString) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | Der XML-String des neuen hinzuzufügenden Teils. |

### Rückgabewert

Erstellter benutzerdefinierter XML-Teil.

## CustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) Methode


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die XML-Daten des neuen hinzuzufügenden Teils. |

### Rückgabewert

Erstellter benutzerdefinierter XML-Teil.

## CustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) Methode


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
System::SharedPtr<ICustomXmlPart> Aspose::Slides::CustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der inputStream mit XML-Daten des neuen hinzuzufügenden Teils. |

### Rückgabewert

Erstellter benutzerdefinierter XML-Teil.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICustomXmlPart](../../icustomxmlpart/)
* Klasse [String](../../../system/string/)
* Klasse [CustomXmlPartCollection](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)