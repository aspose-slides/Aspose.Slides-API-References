---
title: ToDecimal()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in eine äquivalente Dezimalzahl.
type: docs
weight: 235
url: /de/system/convert/todecimal/
---
## Convert::ToDecimal(bool) Methode

Konvertiert den angegebenen booleschen Wert in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl ohne Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl mit Vorzeichen in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) Methode

Konvertiert die angegebene Fließkommazahl in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) Methode

Konvertiert die angegebene Double-Zahl in eine äquivalente Dezimalzahl.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) Methode

Gibt die angegebene Dezimalzahl zurück.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) Methode

Die Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) Methode

Die Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) Methode

Konvertiert die angegebene Null-String in den entsprechenden [Decimal](../../decimal/) Wert.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Rückgabewert

Null.

## Convert::ToDecimal(const char_t *) Methode

Konvertiert den angegebenen C-String, der die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../../decimal/) Wert.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende C-String |

### Rückgabewert

Der [Decimal](../../decimal/) Wert, der der durch den angegebenen C-String dargestellten Zahl entspricht.

## Convert::ToDecimal(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../../decimal/) Wert.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der [Decimal](../../decimal/) Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../../decimal/) Wert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatinformationen enthält |

### Rückgabewert

Der [Decimal](../../decimal/) Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../../decimal/) Wert unter Verwendung der angegebenen Zahlenstile und Formatierungsinformationen.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl festlegt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatinformationen enthält |

### Rückgabewert

Der [Decimal](../../decimal/) Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen gekapselten Wert in den entsprechenden [Decimal](../../decimal/) Wert.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der Shared-Pointer auf das Objekt, das den zu konvertierenden Wert kapselt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende Format, wenn der Typ des gekapselten Werts [String](../../string/) ist |

### Rückgabewert

Ein [Decimal](../../decimal/) Wert, der dem angegebenen gekapselten Wert entspricht.

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [Object](../../object/)
* Struktur [Convert](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)