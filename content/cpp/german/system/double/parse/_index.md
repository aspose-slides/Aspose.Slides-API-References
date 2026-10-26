---
title: Parse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert.
type: docs
weight: 1
url: /de/system/double/parse/
---
## Double::Parse(const String\&) Methode


Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert.

```cpp
static double System::Double::Parse(const String &value)
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformat-Informationen enthält. |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) Methode



```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode



```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) Methode



```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette, die die String-Darstellung einer Zahl enthält, in den entsprechenden double-Genauigkeits-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenketten-Darstellung einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformat-Informationen enthält. |

### Rückgabewert

Der double-Genauigkeits-Gleitkommawert, der der durch die angegebene Zeichenkette dargestellten Zahl entspricht.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) Methode



```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) Methode



```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) Methode



```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)