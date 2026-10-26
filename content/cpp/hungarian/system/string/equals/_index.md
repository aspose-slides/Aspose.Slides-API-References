---
title: Equals()
second_title: Aspose.Slides for C++ API hivatkozás
description: Karakterlánc egyenlőség összehasonlítás. A StringComparison felsorolás által biztosított több mód támogatott.
type: docs
weight: 391
url: /hu/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const metódus


[String](../) egyenlőség összehasonlítás. A StringComparison enumeration által biztosított több mód támogatott.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a jelenlegivel való összehasonlításhoz. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód (lásd [System::StringComparison](../../stringcomparison/) a részletekért). |

### Visszatérési érték

true, ha a karakterláncok egyeznek a kiválasztott összehasonlítási típussal, egyébként false.

## String::Equals(const String\&) const metódus


[String](../) egyenlőség összehasonlítás. A [System::StringComparison::Ordinal](../../stringcomparison/) összehasonlítási módot használja.

```cpp
bool System::String::Equals(const String &str) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) a jelenlegivel való összehasonlításhoz. |

### Visszatérési érték

true, ha a karakterláncok egyeznek, egyébként false.

## String::Equals(const String\&, const String\&) metódus


Két karakterláncot hasonlít össze az Ordial összehasonlítási móddal.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| strA | const [String](../)\& | Az első összehasonlítandó karakterlánc. |
| strB | const [String](../)\& | A második összehasonlítandó karakterlánc. |

### Visszatérési érték

true, ha a karakterláncok egyeznek, egyébként false.

## String::Equals(const String\&, const String\&, System::StringComparison) metódus


Két karakterláncot hasonlít össze.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| strA | const [String](../)\& | Az első összehasonlítandó karakterlánc. |
| strB | const [String](../)\& | A második összehasonlítandó karakterlánc. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mód. |

### Visszatérési érték

true, ha a karakterláncok egyeznek, egyébként false.

## Lásd még

* Enum [StringComparison](../../stringcomparison/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)