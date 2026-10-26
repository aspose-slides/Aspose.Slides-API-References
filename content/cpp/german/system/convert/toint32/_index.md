---
title: ToInt32()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.
type: docs
weight: 157
url: /de/system/convert/toint32/
---
## Convert::ToInt32(bool) Methode


Konvertiert den angegebenen booleschen Wert in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) Methode


Konvertiert die angegebene 8-bit vorzeichenlose Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) Methode


Konvertiert die angegebene 8-bit vorzeichenbehaftete Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) Methode


Konvertiert die angegebene 16-bit vorzeichenlose Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) Methode


Konvertiert die angegebene 16-bit vorzeichenbehaftete Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) Methode


Konvertiert die angegebene 32-bit vorzeichenlose Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) Methode


Gibt das angegebene 32-bit vorzeichenbehaftete Integer zurück.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) Methode


Konvertiert die angegebene 64-bit vorzeichenlose Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) Methode


Konvertiert die angegebene 64-bit vorzeichenbehaftete Ganzzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) Methode


Konvertiert die angegebene Fließkommazahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) Methode


Konvertiert die angegebene Doppel-Fließkommazahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) Methode


Konvertiert die angegebene Dezimalzahl in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) Methode


Konvertiert das angegebene Unicode-Zeichen in ein äquivalentes 32-bit vorzeichenbehaftetes Integer.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) Methode


Konvertierung wird nicht unterstützt. Wirft immer eine InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) Methode


Konvertiert die angegebene Null-Zeichenkette in den äquivalenten 32-bit Integer-Wert.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToInt32(const char_t *) Methode


Konvertiert den angegebenen C-String, der die Zeichenkettendarstellung einer Zahl enthält, in den äquivalenten 32-bit Integer-Wert.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende C-String |

### Rückgabewert

Der 32-bit Integer-Wert, der der durch den angegebenen C-String dargestellten Zahl entspricht

## Convert::ToInt32(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl enthält, in den äquivalenten 32-bit Integer-Wert.

```cpp
static int System::Convert::ToInt32(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der 32-bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt32(const String\&, int) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl in der angegebenen Basis enthält, in den äquivalenten 32-bit Integer-Wert.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| from_base | int | Die Basis der durch die Zeichenkette dargestellten Zahl |

### Rückgabewert

Der 32-bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl enthält, in den äquivalenten 32-bit Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformat-Informationen enthält |

### Rückgabewert

Der 32-bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) Methode




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die Zeichenkettendarstellung einer Zahl enthält, in den äquivalenten 32-bit Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettendarstellung einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformat-Informationen enthält |

### Rückgabewert

Der 32-bit Integer-Wert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) Methode




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen verpackten Wert in einen äquivalenten 32-bit Integer-Wert.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der Shared-Pointer auf das Objekt, das den zu konvertierenden Wert enthält |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das Zeichenkettenformat, das verwendet wird, wenn der Typ des verpackten Werts [String](../../string/) ist |

### Rückgabewert

Ein 32-bit Integer-Wert, der dem angegebenen verpackten Wert entspricht

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