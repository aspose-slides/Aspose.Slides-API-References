---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt einen neuen benutzerdefinierten XML-Teil hinzu.
type: docs
weight: 14
url: /de/aspose.slides/icustomxmlpartcollection/add/
---
## ICustomXmlPartCollection::Add(System::ArrayPtr\<uint8_t\>) Methode

Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::ArrayPtr<uint8_t> xmlData)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Die XML-Daten des neuen Teils, das hinzugefügt werden soll. |

### Rückgabewert

Erstellt ein benutzerdefiniertes XML-Teil.

## ICustomXmlPartCollection::Add(System::String) Methode

Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::String xmlString)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlString | [System::String](../../../system/string/) | Der XML-String des neuen Teils, das hinzugefügt werden soll. |

### Rückgabewert

Erstellt ein benutzerdefiniertes XML-Teil.

## ICustomXmlPartCollection::Add(System::SharedPtr\<System::IO::Stream\>) Methode

Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

```cpp
virtual System::SharedPtr<ICustomXmlPart> Aspose::Slides::ICustomXmlPartCollection::Add(System::SharedPtr<System::IO::Stream> inputStream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Der inputStream mit den XML-Daten des neuen Teils, der hinzugefügt werden soll. |

### Rückgabewert

Erstellt ein benutzerdefiniertes XML-Teil.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICustomXmlPart](../../icustomxmlpart/)
* Klasse [ICustomXmlPartCollection](../)
* Klasse [String](../../../system/string/)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)