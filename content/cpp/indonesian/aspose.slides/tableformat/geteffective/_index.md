---
title: GetEffective()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.
type: docs
weight: 40
url: /id/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() metode

Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```

### Nilai Kembalian

Sebuah [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Catatan

Contoh ini menunjukkan cara mendapatkan format isi yang efektif untuk berbagai bagian logika tabel. Harap perhatikan bahwa pemformatan sel selalu memiliki prioritas lebih tinggi daripada pemformatan baris, baris - lebih tinggi daripada kolom, kolom - lebih tinggi daripada seluruh tabel. Jadi pada akhirnya properti CellFormatEffectiveData selalu digunakan untuk menggambar tabel. Kode berikut hanya contoh penggunaan API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Kelas [TableFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)