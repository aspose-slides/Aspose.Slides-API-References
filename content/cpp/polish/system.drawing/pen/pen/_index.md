---
title: Pen()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Tworzy nowy obiekt Pen reprezentujący określony kolor.
type: docs
weight: 1
url: /pl/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) konstruktor

Tworzy nowy [Pen](../) obiekt reprezentujący określony kolor.

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Kolor pióra reprezentowanego przez tworzony obiekt |

## Pen::Pen(const Color\&, float) konstruktor

Tworzy nowy [Pen](../) obiekt reprezentujący określony kolor i szerokość.

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| color | const [Color](../../color/)\& | Kolor pióra reprezentowanego przez tworzony obiekt |
| width | **float** | Szerokość pióra reprezentowanego przez tworzony obiekt |

## Pen::Pen(const SharedPtr\<Brush\>\&) konstruktor

Tworzy nowy [Pen](../) obiekt i inicjalizuje go określonym [Brush](../../brush/) obiektem.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) określający właściwości wypełnienia pióra reprezentowanego przez tworzony obiekt |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) konstruktor

Tworzy nowy [Pen](../) obiekt i inicjalizuje go określonym [Brush](../../brush/) obiektem.

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) określający właściwości wypełnienia pióra reprezentowanego przez tworzony obiekt |
| width | **float** | Szerokość pióra reprezentowanego przez tworzony obiekt |

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Color](../../color/)
* Klasa [Pen](../)
* Klasa [Brush](../../brush/)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)