---
title: Equals()
second_title: Aspose.Slides a C++ API referencia
description: Megállapítja, hogy a megadott terület azonos-e a jelenlegi objektum által a megadott rajzoló felületen képviselt területtel.
type: docs
weight: 157
url: /hu/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) metódus

Megállapítja, hogy a megadott terület azonos-e a jelenlegi objektum által képviselt területtel a megadott rajzoló felületen.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | A terület, amellyel ezt a területet összehasonlítjuk |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Egy rajzoló felület |

### Visszatérési érték

True ha a megadott terület belseje azonos a jelenlegi objektum által képviselt terület belsejével, amikor a **g** paraméterhez rendelt transzformáció alkalmazásra kerül; egyébként - false

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Region](../)
* Osztály [Graphics](../../graphics/)
* Névtér [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)