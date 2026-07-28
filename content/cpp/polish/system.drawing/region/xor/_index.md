---
title: Xor()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Zastępuje obszar reprezentowany przez bieżący obiekt częściami tego obszaru oraz obszaru zdefiniowanego przez określony prostokąt, które nie nachodzą na siebie.
type: docs
weight: 144
url: /pl/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) metoda

Zastępuje obszar reprezentowany przez bieżący obiekt częściami tego obszaru oraz obszaru zdefiniowanego przez określony prostokąt, które nie nachodzą na siebie.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | Prostokąt definiujący obszar, który ma być XOR-owany z obszarem reprezentowanym przez bieżący obiekt |

## Region::Xor(const Rectangle\&) metoda

Zastępuje obszar reprezentowany przez bieżący obiekt częściami tego obszaru oraz obszaru zdefiniowanego przez określony prostokąt, które nie nachodzą na siebie.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Prostokąt definiujący obszar, który ma być XOR-owany z obszarem reprezentowanym przez bieżący obiekt |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) metoda

Zastępuje obszar reprezentowany przez bieżący obiekt częściami tego obszaru oraz ścieżki zdefiniowanej przez określony obiekt, które nie nachodzą na siebie.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Ścieżka definiująca obszar do XOR-owania z obszarem reprezentowanym przez bieżący obiekt |

## Region::Xor(const SharedPtr\<Region\>\&) metoda

Zastępuje obszar reprezentowany przez bieżący obiekt częściami tego obszaru oraz określonego obszaru, które nie nachodzą na siebie.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Obszar, który ma być XOR-owany z obszarem reprezentowanym przez bieżący obiekt |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)