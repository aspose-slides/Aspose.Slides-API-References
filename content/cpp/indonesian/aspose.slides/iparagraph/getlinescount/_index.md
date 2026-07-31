---
title: GetLinesCount()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan jumlah baris dalam paragraf.
type: docs
weight: 105
url: /id/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() metode


Dapatkan jumlah baris dalam paragraf.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### Nilai Kembalian

Jumlah baris dalam paragraf
## Catatan


Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## Lihat Juga

* Kelas [IParagraph](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)