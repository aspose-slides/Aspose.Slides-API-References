---
title: ToUInt16()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in einen äquivalenten 16-bit-vorzeichenlosen Integer.
type: docs
weight: 144
url: /de/system/convert/touint16/
---
## Convert::ToUInt16(bool) Methode

Konvertiert den angegebenen booleschen Wert in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```
## Convert::ToUInt16(uint8_t) Methode

Konvertiert die angegebene 8-bit-vorzeichenlose Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Ganzzahlwert.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```
## Convert::ToUInt16(int8_t) Methode

Konvertiert die angegebene 8-bit-vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```
## Convert::ToUInt16(uint16_t) Methode

Gibt die angegebene 16-bit-vorzeichenlose Ganzzahl zurück.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```
## Convert::ToUInt16(int16_t) Methode

Konvertiert die angegebene 16-bit-vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```
## Convert::ToUInt16(uint32_t) Methode

Konvertiert die angegebene 32-bit-vorzeichenlose Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```
## Convert::ToUInt16(int32_t) Methode

Konvertiert die angegebene 32-bit-vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```
## Convert::ToUInt16(uint64_t) Methode

Konvertiert die angegebene 64-bit-vorzeichenlose Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```
## Convert::ToUInt16(int64_t) Methode

Konvertiert die angegebene 64-bit-vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```
## Convert::ToUInt16(float) Methode

Konvertiert die angegebene Fließkommazahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```
## Convert::ToUInt16(double) Methode

Konvertiert die angegebene Double-Zahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```
## Convert::ToUInt16(const Decimal\&) Methode

Konvertiert die angegebene Dezimalzahl in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```
## Convert::ToUInt16(char_t) Methode

Konvertiert das angegebene Unicode-Zeichen in einen äquivalenten 16-bit-vorzeichenlosen Integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```
## Convert::ToUInt16(DateTime) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```
## Convert::ToUInt16(std::nullptr_t) Methode

Konvertiert den angegebenen Null-String in den entsprechenden vorzeichenlosen 16-bit-Integerwert.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToUInt16(const char_t *) Methode

Konvertiert die angegebene c-string, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 16-bit-Integerwert.

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende c-string |

### Rückgabewert

Der vorzeichenlose 16-bit-Integerwert, der der durch den angegebenen c-string dargestellten Zahl entspricht.

## Convert::ToUInt16(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 16-bit-Integerwert.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der vorzeichenlose 16-bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToUInt16(const String\&, int) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden vorzeichenlosen 16-bit-Integerwert.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der vorzeichenlose 16-bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 16-bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatierungsinformationen für die Zeichenkette enthält |

### Rückgabewert

Der vorzeichenlose 16-bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 16-bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination der Werte des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatierungsinformationen für die Zeichenkette enthält |

### Rückgabewert

Der vorzeichenlose 16-bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) Methode




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen verpackten Wert in einen äquivalenten vorzeichenlosen 16-bit-Integerwert.

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr auf das Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende String-Format, falls der Typ des verpackten Werts [String](../../string/) ist |

### Rückgabewert

Ein vorzeichenloser 16-bit-Integerwert, der dem angegebenen verpackten Wert entspricht.

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)