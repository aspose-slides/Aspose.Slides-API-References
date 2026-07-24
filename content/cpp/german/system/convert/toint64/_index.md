---
title: ToInt64()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.
type: docs
weight: 183
url: /de/system/convert/toint64/
---
## Convert::ToInt64(bool) Methode


Konvertiert den angegebenen booleschen Wert in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) Methode


Konvertiert das angegebene 8-Bit vorzeichenlose Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) Methode


Konvertiert das angegebene 8-Bit vorzeichenbehaftete Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) Methode


Konvertiert das angegebene 16-Bit vorzeichenlose Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) Methode


Konvertiert das angegebene 16-Bit vorzeichenbehaftete Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) Methode


Konvertiert das angegebene 32-Bit vorzeichenlose Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) Methode


Konvertiert das angegebene 32-Bit vorzeichenbehaftete Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) Methode


Konvertiert das angegebene 64-Bit vorzeichenlose Integer in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) Methode


Gibt das angegebene 64-Bit vorzeichenbehaftete Integer zurück.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) Methode


Konvertiert die angegebene Fließkommazahl in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) Methode


Konvertiert die angegebene Double-Zahl in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) Methode


Konvertiert die angegebene Dezimalzahl in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) Methode


Konvertiert das angegebene Unicode-Zeichen in ein entsprechendes 64-Bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) Methode


Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) Methode


Konvertiert die angegebene Null-Zeichenkette in den entsprechenden 64-Bit-Integer-Wert.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToInt64(const char_t *) Methode


Konvertiert den angegebenen C-String, der die Zeichenkettendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Integer-Wert.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende C-String |

### Rückgabewert

Der 64-Bit-Integer-Wert, der der durch den angegebenen C-String dargestellten Zahl entspricht

## Convert::ToInt64(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Integer-Wert.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der 64-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt64(const String\&, int) Methode


Konvertiert die angegebene Zeichenkette, die die Darstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 64-Bit-Integer-Wert.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der 64-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatierungsinformationen enthält |

### Rückgabewert

Der 64-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Darstellung einer Zahl enthält, in den entsprechenden 64-Bit-Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des Enums NumberStyles, die den zulässigen Stil der Zeichenkettendarstellung einer Zahl festlegt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Formatierungsinformationen enthält |

### Rückgabewert

Der 64-Bit-Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) Methode




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen boxed-Wert in einen entsprechenden 64-Bit-Integer-Wert.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der Shared-Pointer auf das Objekt, das den zu konvertierenden Wert enthält |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende Format, falls der Typ des boxed-Werts [String](../../string/) ist |

### Rückgabewert

Ein 64-Bit-Integer-Wert, der dem angegebenen boxed-Wert entspricht

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