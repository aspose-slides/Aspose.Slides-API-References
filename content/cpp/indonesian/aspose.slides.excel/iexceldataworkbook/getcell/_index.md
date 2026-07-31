---
title: GetCell()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil sel dari lembar kerja yang ditentukan menggunakan indeksnya dan koordinat sel.
type: docs
weight: 14
url: /id/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metode


Mengambil sel dari lembar kerja yang ditentukan menggunakan indeksnya dan koordinat sel.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks berbasis nol dari lembar kerja. |
| row | **int32_t** | Indeks baris berbasis nol dari sel. |
| column | **int32_t** | Indeks kolom berbasis nol dari sel. |

### Nilai Kembali

Sel pada lokasi yang ditentukan.
## Catatan



Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metode


Mengambil sel dari lembar kerja yang ditentukan menggunakan namanya dan koordinat sel.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja. |
| row | **int32_t** | Indeks baris berbasis nol dari sel. |
| column | **int32_t** | Indeks kolom berbasis nol dari sel. |

### Nilai Kembali

Sel pada lokasi yang ditentukan.
## Catatan



Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metode


Mengambil sel dari lembar kerja yang ditentukan menggunakan indeksnya dan nama sel gaya Excel (mis., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Indeks berbasis nol dari lembar kerja. |
| cellName | [System::String](../../../system/string/) | Referensi sel gaya Excel (mis., "A1", "C5"). |

### Nilai Kembali

Sel pada lokasi yang ditentukan.
## Catatan



Contoh: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metode


Mengambil sel dari lembar kerja yang ditentukan menggunakan nama sel gaya Excel (mis., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Nama lembar kerja. |
| cellName | [System::String](../../../system/string/) | Referensi sel gaya Excel (mis., "A1", "C5"). |

### Nilai Kembali

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
* Kelas [IExcelDataWorkbook](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::Excel](../../)
* Pustaka [Aspose.Slides](../../../)