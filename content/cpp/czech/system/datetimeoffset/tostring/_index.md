---
title: ToString()
second_title: Aspose.Slides pro C++ API referenci
description: Převádí aktuální objekt na řetězec pomocí určeného formátu a poskytovatele formátu.
type: docs
weight: 443
url: /cs/system/datetimeoffset/tostring/
---
## DateTimeOffset::ToString(const String&, const SharedPtr<IFormatProvider>&) const metoda

Převádí aktuální objekt na řetězec pomocí určeného formátu a poskytovatele formátu.

```cpp
String System::DateTimeOffset::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Řetězec formátu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |

### Návratová hodnota

[String](../../string/) reprezentace aktuálního [DateTimeOffset](../) objektu.

## DateTimeOffset::ToString(const SharedPtr<IFormatProvider>&) const metoda

Převádí aktuální objekt na řetězec pomocí zadaného poskytovatele formátu.

```cpp
String System::DateTimeOffset::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Poskytovatel formátu. |

### Návratová hodnota

[String](../../string/) reprezentace aktuálního [DateTimeOffset](../) objektu.

## DateTimeOffset::ToString(const String&) const metoda

Převádí aktuální objekt na řetězec pomocí určeného formátu.

```cpp
String System::DateTimeOffset::ToString(const String &format) const
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Řetězec formátu. |

### Návratová hodnota

[String](../../string/) reprezentace aktuálního [DateTimeOffset](../) objektu.

## DateTimeOffset::ToString() const metoda

Převádí aktuální objekt na řetězec.

```cpp
String System::DateTimeOffset::ToString() const
```

### Návratová hodnota

[String](../../string/) reprezentace aktuálního [DateTimeOffset](../) objektu.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [DateTimeOffset](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)