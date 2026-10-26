---
title: Enum
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Methoden bereit, die einige Operationen an Werten des Enum-Typs ausführen. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals aus irgendeinem Grund Instanzen davon erstellen.
type: docs
weight: 1587
url: /de/system/enum/
---
## Enum-Struktur

Provides methods that perform some operations on values of enum type. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
template<class E,class Guard>class Enum
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| E | Der Typ der enum, deren Werte von der Klasse behandelt werden |
| Guard | Service-Typ-Argument, dessen Zweck es ist, sicherzustellen, dass **E** ein aufzählbarer Typ ist |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Führt den arithmetischen Vergleich der Werte der angegebenen Aufzählungskonstanten aus. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Gibt den Namen der Aufzählungskonstanten zurück, die den angegebenen Wert hat. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Gibt den Namen der Aufzählungskonstanten zurück, die den angegebenen Wert hat. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Gibt ein Array zurück, das die Namen aller Mitglieder der Aufzählung **E** enthält. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Gibt den zugrunde liegenden Typ der Aufzählung zurück. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Gibt ein Array zurück, das alle Mitglieder der Aufzählung **E** enthält. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Bestimmt, ob die angegebenen Bits in einer Bitdarstellung des angegebenen enum-Wertes gesetzt sind. |
| static **bool** [IsDefined](./isdefined/)(E) | Bestimmt, ob der angegebene Wert ein Mitglied des Aufzählungstyps **E** ist. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Bestimmt, ob der angegebene Wert ein Mitglied des Aufzählungstyps **T** ist. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Bestimmt, ob der Wert mit dem angegebenen Namen zu den Mitgliedern der enum **E** gehört. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Konvertiert die angegebene Zeichenkette in die entsprechende Aufzählungskonstante. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Versucht, die angegebene Zeichenkette in die entsprechende Aufzählungskonstante zu konvertieren. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Versucht, die angegebene Zeichenkette in die entsprechende Aufzählungskonstante zu konvertieren. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias für den zugrunde liegenden Typ der Aufzählung. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)