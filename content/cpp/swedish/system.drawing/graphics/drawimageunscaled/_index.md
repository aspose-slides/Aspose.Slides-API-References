---
title: DrawImageUnscaled()
second_title: Aspose.Slides för C++ API-referens
description: Ritar den angivna bilden med dess ursprungliga fysiska storlek på den angivna platsen.
type: docs
weight: 443
url: /sv/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) metod

Ritar den specificerade bilden med dess ursprungliga fysiska storlek på den angivna platsen.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | int | X-koordinaten för den ritade bildens övre vänstra hörn |
| y | int | Y-koordinaten för den ritade bildens övre vänstra hörn |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) metod

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en angiven plats.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| x | int | X-koordinaten för den ritade bildens övre vänstra hörn |
| y | int | Y-koordinaten för den ritade bildens övre vänstra hörn |
| width | int | Ej använd |
| height | int | Ej använd |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) metod

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en angiven plats.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| rect | const [Rectangle](../../rectangle/)\& | Rektangeln som specificerar den ritade bildens övre vänstra hörn. Rektangelns X- och Y-egenskaper specificerar det övre vänstra hörnet. Bredd- och höjdvärdena ignoreras. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) metod

Ritar en specificerad bild med dess ursprungliga fysiska storlek på en angiven plats.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Bilden att rita |
| point | const [Point](../../point/)\& | Den [Point](../../point/) strukturen som specificerar den ritade bildens övre vänstra hörn. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [Image](../../image/)
* klass [Graphics](../)
* klass [Rectangle](../../rectangle/)
* klass [Point](../../point/)
* namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)