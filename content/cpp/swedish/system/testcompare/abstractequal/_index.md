---
title: AbstractEqual()
second_title: Aspose.Slides för C++ API-referens
description: Jämför två samlingar av okänd typ.
type: docs
weight: 14
url: /sv/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) metod


Jämför två samlingar av okänd typ.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av samlingselement. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Vänster samling. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | Höger samling. |

### Returvärde

Sant om samlingarna matchar (t.ex. båda är null), eller om storlekarna matchar och elementen matchar, falskt annars.

## Se även

* Klass [ICollection](../../../system.collections.generic/icollection/)
* Struktur [TestCompare](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)