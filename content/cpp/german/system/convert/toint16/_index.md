---
title: ToInt16()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert den angegebenen booleschen Wert in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.
type: docs
weight: 131
url: /de/system/convert/toint16/
---
## Convert::ToInt16(bool) Methode


Konvertiert den angegebenen booleschen Wert in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) Methode


Konvertiert die angegebene 8-Bit vorzeichenlose Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) Methode


Konvertiert die angegebene 8-Bit vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) Methode


Konvertiert die angegebene 16-Bit vorzeichenlose Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) Methode


Gibt den angegebenen 16-Bit vorzeichenbehafteten Integer zurück.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) Methode


Konvertiert die angegebene 32-Bit vorzeichenlose Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) Methode


Konvertiert die angegebene 32-Bit vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) Methode


Konvertiert die angegebene 64-Bit vorzeichenlose Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) Methode


Konvertiert die angegebene 64-Bit vorzeichenbehaftete Ganzzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) Methode


Konvertiert die angegebene Fließkommazahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) Methode


Konvertiert die angegebene Doppelpräzisions-Fließkommazahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) Methode


Konvertiert die angegebene Dezimalzahl in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) Methode


Konvertiert das angegebene Unicode-Zeichen in einen äquivalenten 16-Bit vorzeichenbehafteten Integer.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) Methode


Die Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) Methode


Konvertiert die angegebene Nullzeichenkette in den entsprechenden 16-Bit Integer-Wert.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToInt16(const char_t *) Methode


Konvertiert die angegebene C-Zeichenkette, die die Textdarstellung einer Zahl enthält, in den entsprechenden 16-Bit Integer-Wert.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die zu konvertierende C-Zeichenkette |

### Rückgabewert

Der 16-Bit Integer-Wert, der der durch die angegebene C-Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt16(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die Textdarstellung einer Zahl enthält, in den entsprechenden 16-Bit Integer-Wert.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der 16-Bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt16(const String\&, int) Methode


Konvertiert die angegebene Zeichenkette, die die Textdarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 16-Bit Integer-Wert.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der 16-Bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Textdarstellung einer Zahl enthält, in den entsprechenden 16-Bit Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der 16-Bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Textdarstellung einer Zahl enthält, in den entsprechenden 16-Bit Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zahlen-Textdarstellung angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der 16-Bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) Methode




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen boxed-Wert in einen äquivalenten 16-Bit Integer-Wert.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der Shared-Pointer auf das Objekt, das den zu konvertierenden Wert enthält |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende Zeichenkettenformat, falls der Typ des boxed-Werts [String](../../string/) ist |

### Rückgabewert

Ein 16-Bit Integer-Wert, der dem angegebenen boxed-Wert entspricht

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