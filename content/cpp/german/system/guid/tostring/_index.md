---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die vom aktuellen Objekt dargestellte GUID in ihre Stringdarstellung.
type: docs
weight: 79
url: /de/system/guid/tostring/
---
## Guid::ToString() const Methode


Konvertiert die vom aktuellen Objekt dargestellte GUID in ihre Stringdarstellung.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const Methode


Konvertiert die vom aktuellen Objekt dargestellte GUID in ihre Stringdarstellung unter Verwendung des angegebenen Stringformats.

```cpp
String System::Guid::ToString(const String &format) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Das zu verwendende Format |

### Rückgabewert

Die Stringdarstellung des GUID-Werts, der vom aktuellen Objekt dargestellt wird

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const Methode


Konvertiert die vom aktuellen Objekt dargestellte GUID in ihre Stringdarstellung unter Verwendung des angegebenen Stringformats und der Kultur.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Das zu verwendende Format |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Zu verwendende Kultur |

### Rückgabewert

Die Stringdarstellung des GUID-Werts, der vom aktuellen Objekt dargestellt wird

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Guid](../)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)