---
title: get_DrawingGuides()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi panduan menggambar untuk slide handout master. Hanya-baca IDrawingGuidesCollection
type: docs
weight: 14
url: /id/aspose.slides/imasterhandoutslide/get_drawingguides/
---
## IMasterHandoutSlide::get_DrawingGuides() metode

Mengembalikan koleksi panduan menggambar untuk slide handout master. Hanya-baca [IDrawingGuidesCollection](../../idrawingguidescollection/)

```cpp
virtual System::SharedPtr<IDrawingGuidesCollection> Aspose::Slides::IMasterHandoutSlide::get_DrawingGuides()=0
```

## Catatan

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::Drawing::SizeF notesSize = pres->get_NotesSize()->get_Size();
System::SharedPtr<IDrawingGuidesCollection> guides = pres->get_MasterHandoutSlideManager()->SetDefaultMasterHandoutSlide()->get_DrawingGuides();
// Adding the new horizontal drawing guide above the slide center
guides->Add(Orientation::Horizontal, notesSize.get_Height() / 2 - 50.0f);
pres->Save(u"MasterHandoutDrawingGuides_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDrawingGuidesCollection](../../idrawingguidescollection/)
* Kelas [IMasterHandoutSlide](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)