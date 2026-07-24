---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dolgu modu ile GraphicsPath sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) constructor

Belirtilen dolgu modu ile yeni bir [GraphicsPath](../) sınıfı örneği oluşturur.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Oluşturulan nesnenin temsil ettiği kapalı yolun içinin nasıl doldurulacağını belirtir |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Belirtilen yolu temsil eden [GraphicsPath](../) nesnesinin yeni bir örneğini oluşturur.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Oluşturulan nesnenin temsil edeceği yolu belirten noktaları içeren bir dizi |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | İlgili **pts** dizisindeki noktaların tiplerini belirten değerleri içeren bir dizi |
| fillMode | [FillMode](../../fillmode/) | Oluşturulan nesnenin temsil ettiği kapalı yolun içinin nasıl doldurulacağını belirtir |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) constructor

Belirtilen yolu temsil eden [GraphicsPath](../) nesnesinin yeni bir örneğini oluşturur.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Oluşturulan nesnenin temsil edeceği yolu belirten noktaları içeren bir dizi |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | İlgili **pts** dizisindeki noktaların tiplerini belirten değerleri içeren bir dizi |
| fillMode | [FillMode](../../fillmode/) | Oluşturulan nesnenin temsil ettiği kapalı yolun içinin nasıl doldurulacağını belirtir |

## GraphicsPath::GraphicsPath(const SkPath\&) constructor

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Ayrıca Bakınız

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [GraphicsPath](../)
* Sınıf [Point](../../../system.drawing/point/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Ad Alanı [System::Drawing::Drawing2D](../../)
* Kütüphane [Aspose.Slides](../../../)