---
title: SpecifyKind()
second_title: Aspose.Slides a C++ API referencia
description: Létrehoz egy új DateTime objektumot, amely ugyanannyi ticket képvisel, mint a megadott DateTime objektum, és a kind argumentum által megadott módon helyi időt, UTC időt vagy egyik sem képvisel.
type: docs
weight: 833
url: /hu/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) method


Létrehoz egy új [DateTime](../) objektumot, amely ugyanannyi ticket képvisel, mint a megadott [DateTime](../) objektum, és a **kind** argumentum által megadott módon helyi időt, UTC időt vagy egyik sem.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | A [DateTime](../) objektum, amelyből a tickek számát másolja |
| kind | [DateTimeKind](../../datetimekind/) | Megadja, hogy az új objektumnak helyi időt, UTC időt vagy egyik sem kell legyen. |

### Visszatérési érték

Egy új [DateTime](../) objektum, amely ugyanannyi ticket képvisel, mint a **value**, és a **kind** által megadott DateTimeKind értéket.

## Lásd még

* Enum [DateTimeKind](../../datetimekind/)
* Osztály [DateTime](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)