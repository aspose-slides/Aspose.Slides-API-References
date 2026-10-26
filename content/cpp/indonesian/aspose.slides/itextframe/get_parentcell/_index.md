---
title: get_ParentCell()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka ICell. Hanya-baca ICell.
type: docs
weight: 79
url: /id/aspose.slides/itextframe/get_parentcell/
---
## ITextFrame::get_ParentCell() metode

Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka [ICell](../../icell/). Hanya-baca [ICell](../../icell/).

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITextFrame::get_ParentCell()=0
```

## Keterangan

Contoh kode berikut menunjukkan
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICell](../../icell/)
* Kelas [ITextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)