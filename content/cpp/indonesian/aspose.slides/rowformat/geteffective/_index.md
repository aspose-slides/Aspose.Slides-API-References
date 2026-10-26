---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan properti format baris tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.
type: docs
weight: 1
url: /id/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() metode

Mendapatkan properti format baris tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### Nilai Kembali

Sebuah [IRowFormatEffectiveData](../../irowformateffectivedata/).

## Catatan

Contoh ini menunjukkan cara mendapatkan format isi yang efektif untuk berbagai bagian logika tabel. Harap perhatikan bahwa pemformatan sel selalu memiliki prioritas lebih tinggi daripada pemformatan baris, baris - lebih tinggi daripada kolom, kolom - lebih tinggi daripada seluruh tabel. Jadi pada akhirnya properti CellFormatEffectiveData selalu digunakan untuk menggambar tabel. Kode berikut hanyalah contoh API. 

```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Output dan perbandingan
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Kelas [RowFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)