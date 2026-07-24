---
title: ToSByte()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in ein entsprechendes vorzeichenbehaftetes 8-bit Integer.
type: docs
weight: 105
url: /de/system/convert/tosbyte/
---
## Convert::ToSByte(bool) Methode

Konvertiert den angegebenen booleschen Wert in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) Methode

Konvertiert die angegebene 8-Bit-vorzeichenlose ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) Methode

Gibt die angegebene 8-Bit-vorzeichenbehaftete ganze Zahl zurück.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) Methode

Konvertiert die angegebene 16-Bit-vorzeichenlose ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) Methode

Konvertiert die angegebene 16-Bit-vorzeichenbehaftete ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) Methode

Konvertiert die angegebene 32-Bit-vorzeichenlose ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) Methode

Konvertiert die angegebene 32-Bit-vorzeichenbehaftete ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) Methode

Konvertiert die angegebene 64-Bit-vorzeichenlose ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) Methode

Konvertiert die angegebene 64-Bit-vorzeichenbehaftete ganze Zahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) Methode

Konvertiert die angegebene Fließkommazahl (float) in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) Methode

Konvertiert die angegebene Fließkommazahl (double) in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) Methode

Konvertiert die angegebene Dezimalzahl in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) Methode

Konvertiert das angegebene Unicode-Zeichen in ein entsprechendes vorzeichenbehaftetes 8-Bit-Integer.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) Methode

Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) Methode

Konvertiert die angegebene Null-Zeichenkette in den entsprechenden 8-Bit-Integer-Wert.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToSByte(const char_t *) Methode

Konvertiert den angegebenen C-String, der die textuelle Darstellung einer Zahl enthält, in den entsprechenden 8-Bit-Integer-Wert.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der C-String, der konvertiert werden soll |

### Rückgabewert

Der 8-Bit-Integer-Wert, der der durch den angegebenen C-String dargestellten Zahl entspricht.

## Convert::ToSByte(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden 8-Bit-Integer-Wert.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der 8-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSByte(const String\&, int) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 8-Bit-Integer-Wert.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der 8-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integer-Wert mittels der bereitgestellten Formatierungsinformationen.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden 8-Bit-Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination der Werte der NumberStyles-Enum, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) Methode




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen verpackten Wert in einen entsprechenden 8-Bit-Integer-Wert.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr auf das Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende Zeichenkettenformat, falls der Typ des verpackten Wertes [String](../../string/) ist |

### Rückgabewert

Ein 8-Bit-Integer-Wert, der dem angegebenen verpackten Wert entspricht.

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
* Struct [Enum](../../enum/)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)