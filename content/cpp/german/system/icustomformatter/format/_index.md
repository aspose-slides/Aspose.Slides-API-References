---
title: Format()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Zeichenkettenrepräsentation eines Werts zurück, der vom aktuellen Objekt unter Verwendung des angegebenen Formats dargestellt wird.
type: docs
weight: 1
url: /de/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) Methode

Gibt eine Zeichenkettenrepräsentation eines Werts zurück, der vom aktuellen Objekt unter Verwendung des angegebenen Formats dargestellt wird.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | [System::String](../../string/) | Das Zeichenkettenformat |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Das zu formatierende Objekt |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Das Objekt, das die Formatierungsinformationen bereitstellt |

### Rückgabewert

Die Zeichenkettenrepräsentation von **arg**, formatiert gemäß dem von **format** und **formatProvider** angegebenen Format

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Object](../../object/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [ICustomFormatter](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)