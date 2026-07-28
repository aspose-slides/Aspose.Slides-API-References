---
title: Equals< float, float >()
second_title: Aspose.Slides C++ API referenciája
description: "Specializáció egyszeres pontosságú lebegőpontos értékekhez. Bár két lebegőpontos NaN-t az IEC 60559:1989 úgy definiál, hogy mindig egyenlőtlennel egyenlőek, a System.Object.Equals szerződése előírja, hogy a felülírásoknak meg kell felelniük egy ekvivalencia operátor követelményeinek. Ezért a System.Double.Equals és a System.Single.Equals True értéket ad vissza, ha két NaN-t hasonlítanak össze, míg az egyenlőség operátor ebben az esetben False értéket ad vissza, ahogyan a szabvány előírja."
type: docs
weight: 2705
url: /hu/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) függvény

Specializáció egyszeres pontosságú lebegőpontos értékekhez. Bár két lebegőpontos NaN-t az IEC 60559:1989 úgy definiál, hogy mindig egyenlőtlennel egyenlőek, a [System.Object.Equals](../object/equals/) szerződése előírja, hogy a felülírásoknak meg kell felelniük az ekvivalencia operátor követelményeinek. Ezért a System.Double.Equals és a System.Single.Equals True értéket ad vissza, ha két NaN-t hasonlítanak össze, míg az egyenlőség operátor ebben az esetben False értéket ad vissza, ahogyan a szabvány előírja.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| a | const **float**\& | Az első összehasonlítandó |
| b | const **float**\& | A második összehasonlítandó |

### Visszatérési érték

True, ha mindkét érték NaN vagy egyenlő, egyébként - false

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)