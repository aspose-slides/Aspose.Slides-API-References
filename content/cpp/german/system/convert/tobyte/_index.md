---
title: ToByte()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert den angegebenen booleschen Wert in einen entsprechenden 8-Bit-vorzeichenlosen Integer.
type: docs
weight: 92
url: /de/system/convert/tobyte/
---
## Convert::ToByte(bool) Methode


Konvertiert den angegebenen booleschen Wert in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) Methode


Gibt den angegebenen 8-Bit-vorzeichenlosen Integer zurück.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) Methode


Konvertiert den angegebenen 8-Bit-vorzeichenbehafteten Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) Methode


Konvertiert den angegebenen 16-Bit-vorzeichenlosen Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) Methode


Konvertiert den angegebenen 16-Bit-vorzeichenbehafteten Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) Methode


Konvertiert den angegebenen 32-Bit-vorzeichenlosen Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) Methode


Konvertiert den angegebenen 32-Bit-vorzeichenbehafteten Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) Methode


Konvertiert den angegebenen 64-Bit-vorzeichenlosen Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) Methode


Konvertiert den angegebenen 64-Bit-vorzeichenbehafteten Integer in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) Methode


Konvertiert die angegebene Fließkommazahl (float) in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) Methode


Konvertiert die angegebene Fließkommazahl (double) in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) Methode


Konvertiert die angegebene Dezimalzahl in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) Methode


Konvertiert das angegebene Unicode-Zeichen in einen entsprechenden 8-Bit-vorzeichenlosen Integer.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) Methode


Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) Methode


Konvertiert die angegebene Null-Zeichenkette in den entsprechenden vorzeichenlosen 8-Bit-Integerwert.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToByte(const char_t *) Methode


Konvertiert die angegebene C-Zeichenkette, die die Zeichenrepräsentation einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integerwert.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu konvertierende C-Zeichenkette |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integerwert, der der durch die angegebene C-Zeichenkette dargestellten Zahl entspricht

## Convert::ToByte(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenrepräsentation einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integerwert.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToByte(const String\&, int) Methode


Konvertiert die angegebene Zeichenkette, die die Darstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integerwert.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenrepräsentation einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatierungsinformationen enthält |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenrepräsentation einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten der NumberStyles-Aufzählung, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatierungsinformationen enthält |

### Rückgabewert

Der vorzeichenlose 8-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) Methode




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen verpackten Wert in einen entsprechenden vorzeichenlosen 8-Bit-Integerwert.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der gemeinsam genutzte Zeiger auf das Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das Zeichenkettenformat, das verwendet werden soll, wenn der Typ des verpackten Wertes [String](../../string/) ist |

### Rückgabewert

Ein vorzeichenloser 8-Bit-Integerwert, der dem angegebenen verpackten Wert entspricht

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
* Struktur [Convert](../)
* Struktur [Enum](../../enum/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)