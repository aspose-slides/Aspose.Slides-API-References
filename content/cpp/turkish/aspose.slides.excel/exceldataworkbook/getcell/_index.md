---
title: GetCell()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır.
type: docs
weight: 27
url: /tr/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metodu


Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının sıfır tabanlı dizini. |
| row | **int32_t** | Hücrenin sıfır tabanlı satır indeksi. |
| column | **int32_t** | Hücrenin sıfır tabanlı sütun indeksi. |

### Return Value

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metodu


Belirtilen çalışma sayfasından, adını ve hücre koordinatlarını kullanarak bir hücre alır.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Çalışma sayfasının adı. |
| row | **int32_t** | Hücrenin sıfır tabanlı satır indeksi. |
| column | **int32_t** | Hücrenin sıfır tabanlı sütun indeksi. |

### Return Value

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) metodu


Belirtilen çalışma sayfasından, dizini ve Excel biçimindeki hücre adını (ör. "B2") kullanarak bir hücre alır.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının sıfır tabanlı dizini. |
| cellName | [System::String](../../../system/string/) | Excel biçimindeki hücre referansı (ör. "A1", "C5"). |

### Return Value

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) metodu


Excel biçimindeki hücre adını (ör. "B2") kullanarak belirtilen çalışma sayfasından bir hücre alır.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Çalışma sayfasının adı. |
| cellName | [System::String](../../../system/string/) | Excel biçimindeki hücre referansı (ör. "A1", "C5"). |

### Return Value

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IExcelDataCell](../../iexceldatacell/)
* Sınıf [ExcelDataWorkbook](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)