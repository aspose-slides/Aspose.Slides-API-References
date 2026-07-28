---
title: ToString()
second_title: Aspose.Slides for C++ API referencia
description: A megadott formátum és formátumszolgáltató használatával alakítja a jelenlegi objektumot karakterlánccá.
type: docs
weight: 443
url: /hu/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metódus

A jelenlegi objektumot a megadott formátum és formátumszolgáltató használatával karakterlánccá konvertálja.

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátum karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |

### Visszatérési érték

[String](../../string/) a jelenlegi [DateTimeOffset](../) objektum ábrázolása.

## DateTimeOffset::ToString(const SharedPtr\<IFormatProvider\>\&) const metódus

A megadott formátumszolgáltató használatával alakítja a jelenlegi objektumot karakterlánccá.

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |

### Visszatérési érték

[String](../../string/) a jelenlegi [DateTimeOffset](../) objektum ábrázolása.

## DateTimeOffset::ToString(const String\&) const metódus

A megadott formátum használatával alakítja a jelenlegi objektumot karakterlánccá.

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátum karakterlánc. |

### Visszatérési érték

[String](../../string/) a jelenlegi [DateTimeOffset](../) objektum ábrázolása.

## DateTimeOffset::ToString() const metódus

A jelenlegi objektumot karakterlánccá konvertálja.

```cpp
String System::DateTimeOffset::ToString() const
```

### Visszatérési érték

[String](../../string/) a jelenlegi [DateTimeOffset](../) objektum ábrázolása.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [DateTimeOffset](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)