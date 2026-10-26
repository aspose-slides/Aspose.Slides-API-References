---
title: SplitTextByColumns()
second_title: Referensi API Aspose.Slides untuk C++
description: Memisahkan konten teks dari ITextFrame menjadi sebuah array string,  di mana setiap elemen berkorespondensi dengan kolom teks terpisah dalam bingkai.
type: docs
weight: 144
url: /id/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metode


Memisahkan konten teks dari [ITextFrame](../../itextframe/) menjadi sebuah array string, 

 di mana setiap elemen berkorespondensi dengan kolom teks terpisah dalam bingkai.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Nilai Kembalian

Sebuah array string, di mana setiap string mewakili konten teks dari kolom tertentu 

 dalam [ITextFrame](../../itextframe/).
## Catatan



Jika bingkai teks tidak berisi beberapa kolom, array yang dikembalikan akan memiliki satu elemen 

 yang berisi seluruh teks. 

 Kolom kosong akan direpresentasikan sebagai string kosong dalam array. 

Contoh berikut menunjukkan cara menggunakan [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [TextFrame](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)