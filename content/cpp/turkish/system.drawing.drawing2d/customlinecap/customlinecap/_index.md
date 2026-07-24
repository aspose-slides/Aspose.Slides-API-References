---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen özelliklere sahip kullanıcı tanımlı bir çizgi ucu temsil eden CustomLineCap sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) yapıcı


Belirtilen özelliklere sahip kullanıcı tanımlı bir çizgi ucu temsil eden yeni bir [CustomLineCap](../) sınıfı oluşturur.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Özel uç için dolgu belirtir |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Özel ucun bir dış hatını belirtir |
| baseCap | [LineCap](../../linecap/) | Özel ucun oluşturulduğu temel çizgi ucu |
| baseInset | **float** | Çizgi ile uç arasındaki mesafeyi belirtir |

## Ayrıca Bakınız

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [GraphicsPath](../../graphicspath/)
* Sınıf [CustomLineCap](../)
* Ad alanı [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)