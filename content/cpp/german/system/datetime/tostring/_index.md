---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Zeichenkettenrepräsentation des Datums- und Uhrzeitwerts zurück, der vom aktuellen Objekt dargestellt wird, und verwendet die Formatierungskonventionen, die durch die aktuelle Kultur definiert sind.
type: docs
weight: 482
url: /de/system/datetime/tostring/
---
## DateTime::ToString() const Methode


Gibt die Zeichenkettenrepräsentation des Datums- und Uhrzeitwerts zurück, der vom aktuellen Objekt dargestellt wird, und verwendet dabei die Formatierungskonventionen, die durch die aktuelle Kultur definiert sind.

```cpp
String System::DateTime::ToString() const
```


### Rückgabewert

Die Zeichenkettenrepräsentation des vom aktuellen Objekt dargestellten Wertes

## DateTime::ToString(const String\&) const Methode


Gibt eine Zeichenkettenrepräsentation des Datums- und Uhrzeitwerts zurück, der vom aktuellen Objekt dargestellt wird, und verwendet das angegebene Format sowie die Formatierungskonventionen, die durch die aktuelle Kultur definiert sind.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Eine Formatzeichenkette |

### Rückgabewert

Die Zeichenkettenrepräsentation des vom aktuellen Objekt dargestellten Wertes, formatiert gemäß dem durch **format** definierten Format und der aktuellen Kultur.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const Methode


Gibt eine Zeichenkettenrepräsentation des Datums- und Uhrzeitwerts zurück, der vom aktuellen Objekt dargestellt wird, und verwendet die angegebenen Formatinformationen.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Objekt, das die Formatinformationen darstellt |

### Rückgabewert

Die Zeichenkettenrepräsentation des vom aktuellen Objekt dargestellten Wertes, formatiert gemäß den von **formatProvider** bereitgestellten Formatinformationen.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const Methode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const Methode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const Methode




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const Methode


Gibt eine Zeichenkettenrepräsentation des Datums- und Uhrzeitwerts zurück, der vom aktuellen Objekt dargestellt wird, und verwendet die angegebenen Formatinformationen.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | const [String](../../string/)\& | Eine Formatzeichenkette |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ein Objekt, das die Formatinformationen darstellt |

### Rückgabewert

Die Zeichenkettenrepräsentation des vom aktuellen Objekt dargestellten Wertes, formatiert gemäß den von **provider** bereitgestellten Formatinformationen und der Formatzeichenkette **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const Methode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const Methode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const Methode




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [DateTime](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)