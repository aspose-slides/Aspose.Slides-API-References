---
title: GetBasePlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang bentuk saat ini diwarisi).
type: docs
weight: 573
url: /id/aspose.slides/ishape/getbaseplaceholder/
---
## IShape::GetBasePlaceholder() metode

Mengembalikan bentuk placeholder dasar (bentuk dari tata letak dan/atau slide master yang bentuk saat ini diwarisi).

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShape::GetBasePlaceholder()=0
```

## Catatan

Null dikembalikan jika bentuk saat ini tidak diwarisi.

```cpp
// ambil semua efek animasi (master/layout/slide) dari bentuk placeholder
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"sample.pptx");

System::SharedPtr<ISlide> slide = pres->get_Slide(0);
System::SharedPtr<IShape> shape = slide->get_Shape(0);
System::ArrayPtr<System::SharedPtr<IEffect>> shapeEffects = slide->get_Timeline()->get_MainSequence()->GetEffectsByShape(shape);

System::SharedPtr<IShape> layoutShape = shape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> layoutShapeEffects = slide->get_LayoutSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(layoutShape);

System::SharedPtr<IShape> masterShape = layoutShape->GetBasePlaceholder();
System::ArrayPtr<System::SharedPtr<IEffect>> masterShapeEffects = slide->get_LayoutSlide()->get_MasterSlide()->get_Timeline()->get_MainSequence()->GetEffectsByShape(masterShape);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)