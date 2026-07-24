---
title: TryParse()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden Decimal-Wert.
type: docs
weight: 482
url: /de/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../) Wert.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge |
| result | [Decimal](../)\& | Die Referenz auf eine [Decimal](../) Variable, in der das Ergebnis der Konvertierung abgelegt wird |

### Rückgabewert

True, wenn die Konvertierung erfolgreich war, sonst - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) Methode


Konvertiert die angegebene Zeichenfolge, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](../) Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die zu konvertierende Zeichenfolge |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Eine bitweise Kombination von Werten des NumberStyles-Enums, die den zulässigen Stil der Zeichenkettenrepräsentation einer Zahl angibt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Zeiger auf ein Objekt, das die Zeichenformatinformationen enthält |
| result | [Decimal](../)\& | Ein Ausgabeparameter; enthält das Ergebnis der Konvertierung |

### Rückgabewert

True, wenn die Konvertierung erfolgreich war, sonst - false

## Siehe auch

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Decimal](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)