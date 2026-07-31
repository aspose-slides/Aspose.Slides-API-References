---
title: get_ParentShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka IShape Read-only IShape.
type: docs
weight: 92
url: /id/aspose.slides/textframe/get_parentshape/
---
## TextFrame::get_ParentShape() metode


Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka [IShape](../../ishape/) Hanya-baca [IShape](../../ishape/).

```cpp
System::SharedPtr<IShape> Aspose::Slides::TextFrame::get_ParentShape() override
```

## Catatan


Contoh kode berikut menunjukkan 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<AutoShape> autoShape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(autoShape->get_TextFrame()->get_ParentShape() == autoShape);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [TextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)