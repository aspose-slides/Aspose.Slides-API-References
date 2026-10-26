---
title: Pen()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy új Pen objektumot, amely a megadott színt képviseli.
type: docs
weight: 1
url: /hu/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) konstruktor

Létrehoz egy új [Pen](../) objektumot, amely a megadott színt képviseli.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| color | const [Color](../../color/)\& | A toll színe, amelyet a létrehozandó objektum képvisel |

## Pen::Pen(const Color\&, float) konstruktor

Létrehoz egy új [Pen](../) objektumot, amely a megadott színt és szélességet képviseli.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| color | const [Color](../../color/)\& | A toll színe, amelyet a létrehozandó objektum képvisel |
| width | **float** | A toll szélessége, amelyet a létrehozandó objektum képvisel |

## Pen::Pen(const SharedPtr\<Brush\>\&) konstruktor

Létrehoz egy új [Pen](../) objektumot, és a megadott [Brush](../../brush/) objektummal inicializálja.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objektum, amely meghatározza a létrehozott objektum által képviselt toll kitöltési tulajdonságait |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) konstruktor

Létrehoz egy új [Pen](../) objektumot, és a megadott [Brush](../../brush/) objektummal inicializálja.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objektum, amely meghatározza a létrehozott objektum által képviselt toll kitöltési tulajdonságait |
| width | **float** | A toll szélessége, amelyet a létrehozandó objektum képvisel |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Color](../../color/)
* Osztály [Pen](../)
* Osztály [Brush](../../brush/)
* Névtere [System::Drawing](../../)
* Könyvtár [Aspose.Slides](../../../)