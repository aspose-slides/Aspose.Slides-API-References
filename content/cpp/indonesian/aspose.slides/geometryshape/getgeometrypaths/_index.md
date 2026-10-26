---
title: GetGeometryPaths()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan salinan jalur bentuk geometri. Koordinat relatif terhadap sudut kiri atas bentuk.
type: docs
weight: 53
url: /id/aspose.slides/geometryshape/getgeometrypaths/
---
## GeometryShape::GetGeometryPaths() metode

Mengembalikan salinan jalur dari bentuk geometri. Koordinat relatif terhadap sudut kiri atas bentuk.

```cpp
System::ArrayPtr<System::SharedPtr<IGeometryPath>> Aspose::Slides::GeometryShape::GetGeometryPaths() override
```

### Nilai Kembali

Array of [IGeometryPath](../../igeometrypath/)
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
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)