---
title: ToSingle()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.
type: docs
weight: 209
url: /de/system/convert/tosingle/
---
## Convert::ToSingle(bool) Methode

Konvertiert den angegebenen booleschen Wert in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) Methode

Gibt die angegebene Fließkommazahl zurück.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) Methode

Konvertiert die angegebene Gleitkommazahl mit doppelter Genauigkeit in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) Methode

Konvertiert die angegebene Dezimalzahl in eine äquivalente Gleitkommazahl mit einfacher Genauigkeit.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) Methode

Konvertierung wird nicht unterstützt. Wirft immer eine InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) Methode

Konvertierung wird nicht unterstützt. Wirft immer eine InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) Methode

Konvertiert die angegebene Null-Zeichenkette in den entsprechenden Gleitkommawert mit einfacher Genauigkeit.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Rückgabewert

Zero.

## Convert::ToSingle(const char_t *) Methode

Konvertiert die angegebene C-Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu konvertierende C-Zeichenkette |

### Rückgabewert

Der Gleitkommawert mit einfacher Genauigkeit, der der in der angegebenen C-Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSingle(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der Gleitkommawert mit einfacher Genauigkeit, der der in der angegebenen Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der Gleitkommawert mit einfacher Genauigkeit, der der in der angegebenen Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) Methode




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine Bit-weise Kombination von Werten des Enums NumberStyles, die den zulässigen Stil der Zeichenfolgendarstellung einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der Gleitkommawert mit einfacher Genauigkeit, der der in der angegebenen Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen verpackten Wert in einen Gleitkommawert mit einfacher Genauigkeit.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr zu dem Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das Zeichenkettenformat, das verwendet werden soll, wenn der Typ des verpackten Werts [String](../../string/) ist |

### Rückgabewert

Ein Gleitkommawert mit einfacher Genauigkeit, der dem angegebenen verpackten Wert entspricht.

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasse [Object](../../object/)
* Struct [Convert](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)