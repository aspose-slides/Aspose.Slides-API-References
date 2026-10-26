---
title: CustomLineCap()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari kelas CustomLineCap yang mewakili cap garis yang ditentukan pengguna dengan properti yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) konstruktor

Membuat sebuah instance baru dari kelas [CustomLineCap](../) yang mewakili sebuah cap garis yang ditentukan pengguna dengan properti yang ditentukan.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Menentukan isi untuk cap khusus |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | Menentukan garis luar dari cap khusus |
| baseCap | [LineCap](../../linecap/) | Cap garis dasar dari mana cap khusus dibuat |
| baseInset | **float** | Menentukan jarak antara garis dan cap |

## Lihat Juga

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)