---
title: GetCell()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil sel dari lembar kerja yang ditentukan menggunakan indeks dan koordinat selnya.
type: docs
weight: 27
url: /id/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metode

Mengambil sel dari lembar kerja yang ditentukan menggunakan indeks dan koordinat selnya.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks berbasis nol dari lembar kerja. |
| row | **int32_t** | Indeks baris berbasis nol dari sel. |
| column | **int32_t** | Indeks kolom berbasis nol dari sel. |

### Nilai Kembalian

Sel pada lokasi yang ditentukan.

## Catatan

Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metode

Mengambil sel dari lembar kerja yang ditentukan menggunakan nama dan koordinat selnya.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja. |
| row | **int32_t** | Indeks baris berbasis nol dari sel. |
| column | **int32_t** | Indeks kolom berbasis nol dari sel. |

### Nilai Kembalian

Sel pada lokasi yang ditentukan.

## Catatan

Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metode

Mengambil sel dari lembar kerja yang ditentukan menggunakan indeks dan nama sel gaya Excel (misalnya "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks berbasis nol dari lembar kerja. |
| cellName | [System::String](../../../system/string/) | Referensi sel gaya Excel (misalnya "A1", "C5"). |

### Nilai Kembalian

Sel pada lokasi yang ditentukan.

## Catatan

Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metode

Mengambil sel dari lembar kerja yang ditentukan menggunakan nama sel gaya Excel (misalnya "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja. |
| cellName | [System::String](../../../system/string/) | Referensi sel gaya Excel (misalnya "A1", "C5"). |

### Nilai Kembalian

Sel pada lokasi yang ditentukan.

## Catatan

Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IExcelDataCell](../../iexceldatacell/)
* Kelas [ExcelDataWorkbook](../)
* Kelas [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)