---
title: CompareOrdinal()
second_title: Aspose.Slides C++ API-referencia
description: Kevesebb-egyenlő-nagyobb összehasonlít két karakterláncot ordinális módban.
type: docs
weight: 833
url: /hu/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) metódus

Kevesebb-egyenlő-nagyobb összehasonlít két karakterláncot ordinális módban.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| strA | const [String](../)\& | Az első összehasonlítandó karakterlánc. |
| strB | const [String](../)\& | A második összehasonlítandó karakterlánc. |

### Visszatérési érték

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla ha megegyeznek, pozitív érték egyébként.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) metódus

Kevesebb-egyenlő-nagyobb összehasonlít két karakterláncot ordinális módban.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| strA | const [String](../)\& | Az első összehasonlítandó karakterlánc. |
| indexA | int | Az első karakterlánc részkarakterláncának kezdete. |
| strB | const [String](../)\& | A második összehasonlítandó karakterlánc. |
| indexB | int | A második karakterlánc részkarakterláncának kezdete. |
| length | int | Az összehasonlítandó karakterek száma. |

### Visszatérési érték

Negatív érték, ha az első részkarakterlánc kisebb a másodiknál, nulla ha megegyeznek, pozitív érték egyébként.

## Lásd még

* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)