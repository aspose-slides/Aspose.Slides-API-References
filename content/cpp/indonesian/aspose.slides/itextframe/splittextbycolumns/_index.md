---
title: SplitTextByColumns()
second_title: Referensi API Aspose.Slides untuk C++
description: Membagi konten teks ITextFrame menjadi sebuah array string, di mana setiap elemen berkorespondensi dengan kolom teks terpisah di dalam frame.
type: docs
weight: 118
url: /id/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metode

Membagi konten teks dari [ITextFrame](../) menjadi sebuah array string, 
di mana setiap elemen berkorespondensi dengan kolom teks terpisah di dalam frame.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### Nilai Kembali

Sebuah array string, di mana setiap string mewakili konten teks dari kolom tertentu di dalam [ITextFrame](../).

## Catatan

Jika frame teks tidak berisi beberapa kolom, array yang dikembalikan akan memiliki satu elemen yang berisi seluruh teks.  

Kolom kosong akan direpresentasikan sebagai string kosong dalam array.  

Contoh berikut menunjukkan cara menggunakan [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Dapatkan shape pertama pada slide dan cast ke ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Bagi konten frame teks menjadi kolom
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Cetak teks setiap kolom ke konsol
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)