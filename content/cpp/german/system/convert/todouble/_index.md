---
title: ToDouble()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen booleschen Wert in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.
type: docs
weight: 222
url: /de/system/convert/todouble/
---
## Convert::ToDouble(bool) Methode

Konvertiert den angegebenen booleschen Wert in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) Methode

Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) Methode

Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) Methode

Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) Methode

Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) Methode

Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) Methode

Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) Methode

Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) Methode

Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) Methode

Konvertiert die angegebene Gleitkommazahl einfacher Genauigkeit in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) Methode

Gibt die angegebene double-Zahl zurück.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) Methode

Konvertiert die angegebene Dezimalzahl in eine äquivalente Gleitkommazahl mit doppelter Genauigkeit.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) Methode

Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) Methode

Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) Methode

Konvertiert die angegebene Null-String in den entsprechenden double-Genauigkeits-Gleitkommawert.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Rückgabewert

Null.

## Convert::ToDouble(const char_t *) Methode

Konvertiert den angegebenen C-String, der die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende C-String |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch den angegebenen C-String dargestellten Zahl entspricht

## Convert::ToDouble(const String\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) Methode




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination der Werte des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatinformationen enthält |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode 




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen verpackten Wert in einen double-Genauigkeits-Gleitkommawert. Wenn der Typ des verpackten Werts [String](../../string/) ist, wird das angegebene Zeichenkettenformat während der Konvertierung verwendet.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr auf das Objekt, das den zu konvertierenden Wert verpackt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das zu verwendende Zeichenkettenformat, falls der Typ des verpackten Werts [String](../../string/) ist |

### Rückgabewert

Ein double-Genauigkeits-Gleitkommawert, der dem angegebenen verpackten Wert entspricht

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)