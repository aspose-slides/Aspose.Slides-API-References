---
title: SetClip()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut Graphics nesnesi tarafından temsil edilen çizim yüzeyinin kırpma bölgesini, mevcut kırpma bölgesi ile belirtilen bölgeyi birleştiren belirtilen işlemin sonucuna ayarlar.
type: docs
weight: 690
url: /tr/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metot

Geçerli [Graphics](../) nesnesi tarafından temsil edilen çizim yüzeyinin kırpma bölgesini, geçerli kırpma bölgesi ile belirtilen bölgeyi birleştiren belirtilen işlemin sonucuna ayarlar.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Birleştirilecek bir bölgeyi belirtir |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Birleştirme işlemini belirtir |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metot

Geçerli [Graphics](../) nesnesi tarafından temsil edilen çizim yüzeyinin kırpma bölgesini, geçerli kırpma bölgesi ile belirtilen bölgeyi birleştiren belirtilen işlemin sonucuna ayarlar.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Birleştirilecek bir bölgeyi belirtir |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Birleştirme işlemini belirtir |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metot

Geçerli [Graphics](../) nesnesi tarafından temsil edilen çizim yüzeyinin kırpma bölgesini, geçerli kırpma bölgesi ile belirtilen bölgeyi birleştiren belirtilen işlemin sonucuna ayarlar.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Birleştirilecek bir bölgeyi belirtir |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Birleştirme işlemini belirtir |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metot

UYGULANMADI.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metot

Geçerli [Graphics](../) nesnesi tarafından temsil edilen çizim yüzeyinin kırpma bölgesini, geçerli kırpma bölgesi ile bir grafik yolu tarafından belirtilen bölgeyi birleştiren belirtilen işlemin sonucuna ayarlar.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Birleştirilecek bir bölgeyi belirtir |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Birleştirme işlemini belirtir |

## Ayrıca Bakınız

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)