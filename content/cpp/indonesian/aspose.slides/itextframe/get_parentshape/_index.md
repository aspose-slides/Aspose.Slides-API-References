---
title: get_ParentShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka IShape Baca-saja IShape.
type: docs
weight: 66
url: /id/aspose.slides/itextframe/get_parentshape/
---
## ITextFrame::get_ParentShape() metode


Mengembalikan shape induk atau null jika objek induk tidak mengimplementasikan antarmuka [IShape](../../ishape/) Baca-saja [IShape](../../ishape/).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::ITextFrame::get_ParentShape()=0
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
* Kelas [ITextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)