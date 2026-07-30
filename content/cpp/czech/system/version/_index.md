---
title: Version
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje číslo verze. Tento typ by měl být alokován na zásobník a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 1470
url: /cs/system/version/
---
## Version třída


Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Version
```

## Metody

| Metoda | Popis |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Porovnává verze reprezentované aktuálním objektem a zadaným objektem. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Určuje, zda jsou čísla verzí reprezentovaná aktuálním a zadaným objektem rovna. |
| int [get_Build](./get_build/)() const | Vrací číslo sestavení. |
| int [get_Major](./get_major/)() const | Vrací hlavní verzi. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Vrací vyšší 16bitovou hodnotu čísla revize. |
| int [get_Minor](./get_minor/)() const | Vrací menší verzi. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Vrací nižší 16bitovou hodnotu čísla revize. |
| int [get_Revision](./get_revision/)() const | Vrací číslo revize. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Převádí řetězcovou reprezentaci čísla verze na ekvivalentní instanci třídy [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci čísla verze reprezentovaného aktuálním objektem. |
| [String](../string/) [ToString](./tostring/)(int) const | Vrací řetězcovou reprezentaci zadaného počtu částí čísla verze reprezentovaného aktuálním objektem. |
|  [Version](./version/)(int, int, int, int) | Vytvoří instanci, která reprezentuje zadané hodnoty hlavní, menší, sestavení a revize. |
|  [Version](./version/)(int, int, int) | Vytvoří instanci, která reprezentuje zadané hodnoty hlavní, menší a sestavení. |
|  [Version](./version/)(int, int) | Vytvoří instanci, která reprezentuje zadané hlavní a hodnoty. |
|  [Version](./version/)(const [String](../string/)\&) | Vytvoří instanci, která reprezentuje číslo verze reprezentované jako řetězec. |
|  [Version](./version/)() | Vytvoří instanci, která reprezentuje číslo verze 0.0.-1.-1. |
## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)