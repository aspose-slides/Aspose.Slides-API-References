---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit.
type: docs
weight: 14
url: /de/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) Methode


Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| result | **float**\& | Die Referenz auf eine Gleitkomma-Variable mit einfacher Genauigkeit, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) Methode


Konvertiert die angegebene Zeichenkette, die die textuelle Darstellung einer Zahl enthält, in den entsprechenden Gleitkommawert mit einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenkette. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der textlichen Darstellung einer Zahl angibt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenkettenformat-Informationen enthält. |
| result | **float**\& | Die Referenz auf eine Gleitkomma-Variable mit einfacher Genauigkeit, in die das Ergebnis der Konvertierung geschrieben wird. |

### Rückgabewert

Wahr, wenn die Konvertierung erfolgreich war, sonst - falsch.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) Methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) Methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) Methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktur [Single](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)