---
title: GetLinesCount()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan jumlah baris dalam sebuah paragraf.
type: docs
weight: 118
url: /id/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() metode


Dapatkan jumlah baris dalam sebuah paragraf.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### Nilai Kembali

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

* Kelas [Paragraph](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)