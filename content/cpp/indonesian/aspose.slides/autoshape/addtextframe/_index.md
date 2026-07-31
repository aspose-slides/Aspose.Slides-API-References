---
title: AddTextFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan TextFrame baru ke sebuah shape. Jika shape sudah memiliki TextFrame, maka hanya mengubah teksnya.
type: docs
weight: 66
url: /id/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) method

Menambahkan [TextFrame](../../textframe/) baru ke sebuah shape. Jika shape sudah memiliki [TextFrame](../../textframe/) maka hanya mengubah teksnya.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Teks default untuk [TextFrame](../../textframe/) baru. |

## Catatan

Kode contoh berikut menunjukkan cara menambahkan teks watermark di PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Contoh berikut menunjukkan cara membuat Text Box pada [Slide](../../slide/).
```cpp
// Membuat instance Presentation
auto pres = System::MakeObject<Presentation>();

// Mendapatkan slide pertama dalam presentasi
auto slide = pres->get_Slides()->idx_get(0);
// Menambahkan AutoShape dengan tipe Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Menambahkan TextFrame ke Rectangle
shape->AddTextFrame(u" ");
// Mengakses text frame
auto txtFrame = shape->get_TextFrame();
// Membuat objek Paragraph untuk text frame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Membuat objek Portion untuk paragraph
auto portion = para->get_Portions()->idx_get(0);
// Mengatur teks
portion->set_Text(u"Aspose TextBox");
// Menyimpan presentasi ke disk
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan kolom dalam Text Box.
```cpp
auto presentation = System::MakeObject<Presentation>();

// Mendapatkan slide pertama dalam presentasi
auto slide = presentation->get_Slides()->idx_get(0);
// Menambahkan AutoShape dengan tipe Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Menambahkan TextFrame ke Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Mendapatkan format teks dari TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Menentukan jumlah kolom dalam TextFrame
format->set_ColumnCount(3);
// Menentukan jarak antar kolom
format->set_ColumnSpacing(10);
// Menyimpan presentasi
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITextFrame](../../itextframe/)
* Kelas [String](../../../system/string/)
* Kelas [AutoShape](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)