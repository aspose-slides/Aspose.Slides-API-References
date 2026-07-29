---
title: Pen()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Pen-objekt som representerar den angivna färgen.
type: docs
weight: 1
url: /sv/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) konstruktor

Skapar ett nytt [Pen](../)-objekt som representerar den angivna färgen.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Färgen på pennan som representeras av objektet som konstrueras |

## Pen::Pen(const Color\&, float) konstruktor

Skapar ett nytt [Pen](../)-objekt som representerar den angivna färgen och bredden.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Färgen på pennan som representeras av objektet som konstrueras |
| width | **float** | Bredden på pennan som representeras av objektet som konstrueras |

## Pen::Pen(const SharedPtr\<Brush\>\&) konstruktor

Skapar ett nytt [Pen](../)-objekt och initierar det med det specificerade [Brush](../../brush/)-objektet.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Det [Brush](../../brush/)-objektet som anger fyllningsattributen för pennan som representeras av objektet som konstrueras |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) konstruktor

Skapar ett nytt [Pen](../)-objekt och initierar det med det specificerade [Brush](../../brush/)-objektet.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Det [Brush](../../brush/)-objektet som anger fyllningsattributen för pennan som representeras av objektet som konstrueras |
| width | **float** | Bredden på pennan som representeras av objektet som konstrueras |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Color](../../color/)
* Klass [Pen](../)
* Klass [Brush](../../brush/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)