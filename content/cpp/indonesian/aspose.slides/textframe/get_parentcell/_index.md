---
title: get_ParentCell()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka ICell. Hanya-baca ICell.
type: docs
weight: 105
url: /id/aspose.slides/textframe/get_parentcell/
---
## TextFrame::get_ParentCell() metode

Mengembalikan sel induk atau null jika objek induk tidak mengimplementasikan antarmuka [ICell](../../icell/). Hanya-baca [ICell](../../icell/).

```cpp
System::SharedPtr<ICell> Aspose::Slides::TextFrame::get_ParentCell() override
```

## Keterangan

Contoh kode berikut menunjukkan 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
System::SharedPtr<Table> table = System::ExplicitCast<Table>(presentation->get_Slide(0)->get_Shape(0));

ASSERT_TRUE(table->idx_get(0, 0)->get_TextFrame()->get_ParentCell() == table->idx_get(0, 0));
```

## Lihat Juga

* TipeDef [SharedPtr](../../../system/sharedptr/)
* Kelas [ICell](../../icell/)
* Kelas [TextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)