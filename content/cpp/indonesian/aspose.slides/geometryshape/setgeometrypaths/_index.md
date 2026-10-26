---
title: SetGeometryPaths()
second_title: Referensi API Aspose.Slides untuk C++
description: "Memperbarui geometri shape dari array IGeometryPath. Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape (ShapeType) menjadi ShapeType::Custom."
type: docs
weight: 79
url: /id/aspose.slides/geometryshape/setgeometrypaths/
---
## GeometryShape::SetGeometryPaths(System::ArrayPtr\<System::SharedPtr\<IGeometryPath\>\>) metode

Memperbarui geometri shape dari array [IGeometryPath](../../igeometrypath/). Koordinat harus relatif terhadap sudut kiri atas shape. Mengubah tipe shape ([ShapeType](../../shapetype/)) menjadi [ShapeType::Custom](../../shapetype/).

```cpp
void Aspose::Slides::GeometryShape::SetGeometryPaths(System::ArrayPtr<System::SharedPtr<IGeometryPath>> geometryPaths) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| geometryPaths | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IGeometryPath](../../igeometrypath/)\>\> | Array jalur geometri |
## Catatan

Contoh: 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>();
auto shape = AsCast<GeometryShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 200.0f, 100.0f));

auto geometryPath = shape->GetGeometryPaths()->idx_get(0);

geometryPath->LineTo(100.0f, 50.0f, 1);
geometryPath->LineTo(100.0f, 50.0f, 4);

shape->SetGeometryPath(geometryPath);

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IGeometryPath](../../igeometrypath/)
* Kelas [GeometryShape](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)