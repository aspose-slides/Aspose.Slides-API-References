---
title: ToString()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a jelenlegi objektum által képviselt GUID-ot annak karakterlánc ábrázolásává.
type: docs
weight: 79
url: /hu/system/guid/tostring/
---
## Guid::ToString() const metódus

Átalakítja a jelenlegi objektum által képviselt GUID-ot annak karakterlánc ábrázolásává.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metódus

Átalakítja a jelenlegi objektum által képviselt GUID-ot a megadott karakterlánc formátum használatával.

```cpp
String System::Guid::ToString(const String &format) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | A használandó formátum |

### Visszatérési érték

A jelenlegi objektum által képviselt GUID érték karakterlánc ábrázolása

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metódus

Átalakítja a jelenlegi objektum által képviselt GUID-ot a megadott karakterlánc formátum és kultúra használatával.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | A használandó formátum |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | A használandó kultúra |

### Visszatérési érték

A jelenlegi objektum által képviselt GUID érték karakterlánc ábrázolása

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [Guid](../)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)