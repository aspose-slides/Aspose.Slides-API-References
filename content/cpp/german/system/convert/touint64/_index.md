---
title: ToUInt64()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert den angegebenen booleschen Wert in ein entsprechendes 64-Bit-vorzeichenloses Integer.
type: docs
weight: 196
url: /de/system/convert/touint64/
---
## Convert::ToUInt64(bool) Methode


Konvertiert den angegebenen booleschen Wert in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) Methode


Konvertiert den angegebenen 8-Bit-vorzeichenlosen Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) Methode


Konvertiert den angegebenen 8-Bit-vorzeichenbehafteten Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) Methode


Konvertiert den angegebenen 16-Bit-vorzeichenlosen Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) Methode


Konvertiert den angegebenen 16-Bit-vorzeichenbehafteten Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) Methode


Konvertiert den angegebenen 32-Bit-vorzeichenlosen Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) Methode


Konvertiert den angegebenen 32-Bit-vorzeichenbehafteten Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) Methode


Gibt den angegebenen 64-Bit-vorzeichenlosen Integer zurück.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) Methode


Konvertiert den angegebenen 64-Bit-vorzeichenbehafteten Integer in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) Methode


Konvertiert die angegebene Fließkommazahl in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) Methode


Konvertiert die angegebene Double-Zahl in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) Methode


Konvertiert die angegebene Dezimalzahl in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) Methode


Konvertiert das angegebene Unicode-Zeichen in ein entsprechendes 64-Bit-vorzeichenloses Integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) Methode


Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) Methode


Konvertiert die angegebene Null-Zeichenkette in den entsprechenden vorzeichenlosen 64-Bit-Integerwert.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToUInt64(const char_t *) Methode


Konvertiert die angegebene C-Zeichenkette, die die Zeichenfolgedarstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 64-Bit-Integerwert.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu konvertierende C-Zeichenkette |

### Rückgabewert

Der vorzeichenlose 64-Bit-Integerwert, der der durch die angegebene C-Zeichenkette dargestellten Zahl entspricht

## Convert::ToUInt64(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenfolgedarstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 64-Bit-Integerwert.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der vorzeichenlose 64-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToUInt64(const String\&, int) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenfolgedarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden vorzeichenlosen 64-Bit-Integerwert.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der vorzeichenlose 64-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenfolgedarstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 64-Bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die String-Formatinformationen enthält |

### Rückgabewert

Der vorzeichenlose 64-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) Methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenfolgedarstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 64-Bit-Integerwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des Enums NumberStyles, die den zulässigen Stil der Zeichenfolgedarstellung einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die String-Formatinformationen enthält |

### Rückgabewert

Der vorzeichenlose 64-Bit-Integerwert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) Methode 




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen Boxed-Wert in einen entsprechenden vorzeichenlosen 64-Bit-Integerwert.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr auf das Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende String-Format, falls der Typ des verpackten Wertes [String](../../string/) ist |

### Rückgabewert

Ein vorzeichenloser 64-Bit-Integerwert, der dem angegebenen verpackten Wert entspricht

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