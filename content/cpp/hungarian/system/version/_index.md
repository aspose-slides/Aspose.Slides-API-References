---
title: Version
second_title: Aspose.Slides C++ API-referencia
description: "Verziószámot reprezentál. Ezt a típust a verembe kell allokálni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt a típus objektumainak kezelésére."
type: docs
weight: 1470
url: /hu/system/version/
---
## Version osztály

A verziószámot reprezentálja. Ezt a típust a verembe kell allokálni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Version
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Összehasonlítja a jelenlegi objektum és a megadott objektum által reprezentált verziókat. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Megállapítja, hogy a jelenlegi és a megadott objektumok által reprezentált verziószámok egyenlőek-e. |
| int [get_Build](./get_build/)() const | Visszaadja az építési számot. |
| int [get_Major](./get_major/)() const | Visszaadja a főverziót. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Visszaadja a revíziószám magas 16-bites értékét. |
| int [get_Minor](./get_minor/)() const | Visszaadja a másodlagos verziót. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Visszaadja a revíziószám alacsony 16-bites értékét. |
| int [get_Revision](./get_revision/)() const | Visszaadja a revíziószámot. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a verziószám karakterlánc ábrázolását egyenértékű [Version](./) osztállyá. |
| [String](../string/) [ToString](./tostring/)() const | Visszaadja egy karakterlánc ábrázolását a jelenlegi objektum által reprezentált verziószámnak. |
| [String](../string/) [ToString](./tostring/)(int) const | Visszaadja a megadott szakaszszám karakterlánc ábrázolását a jelenlegi objektum által reprezentált verziószámnak. |
|  [Version](./version/)(int, int, int, int) | Létrehoz egy példányt, amely a megadott fő, kiseg, építési és revízió értékeket reprezentálja. |
|  [Version](./version/)(int, int, int) | Létrehoz egy példányt, amely a megadott fő, kiseg és építési értékeket reprezentálja. |
|  [Version](./version/)(int, int) | Létrehoz egy példányt, amely a megadott fő és értékeket reprezentálja. |
|  [Version](./version/)(const [String](../string/)\&) | Létrehoz egy példányt, amely a karakterlánc alakban reprezentált verziószámot reprezentálja. |
|  [Version](./version/)() | Létrehoz egy példányt, amely a 0.0.-1.-1. verziószámot reprezentálja. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)