---
title: TryParse()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in das äquivalente 16-Bit-vorzeichenbehaftete Integer.
type: docs
weight: 14
url: /de/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) method


Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in das äquivalente 16-Bit-vorzeichenbehaftete Integer.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| result | **int16_t**\& | Die Referenz auf eine 16-Bit-vorzeichenbehaftete Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Return Value

True, wenn die Konvertierung erfolgreich war, andernfalls - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) method


Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in das äquivalente 16-Bit-vorzeichenbehaftete Integer unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der textuellen Darstellung einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformatierungsinformationen enthält. |
| result | **int16_t**\& | Die Referenz auf eine 16-Bit-vorzeichenbehaftete Integer-Variable, in die das Ergebnis der Konvertierung geschrieben wird. |

### Return Value

True, wenn die Konvertierung erfolgreich war, andernfalls - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) method




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)