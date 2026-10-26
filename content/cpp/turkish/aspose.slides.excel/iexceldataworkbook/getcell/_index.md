---
title: GetCell()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır.
type: docs
weight: 14
url: /tr/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) metod


Belirtilen çalışma sayfasından, dizini ve hücre koordinatlarını kullanarak bir hücre alır.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının sıfır tabanlı dizini. |
| row | **int32_t** | Hücrenin sıfır tabanlı satır dizini. |
| column | **int32_t** | Hücrenin sıfır tabanlı sütun dizini. |

### Dönüş Değeri

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) metod


Belirtilen çalışma sayfasından, adını ve hücre koordinatlarını kullanarak bir hücre alır.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Çalışma sayfasının adı. |
| row | **int32_t** | Hücrenin sıfır tabanlı satır dizini. |
| column | **int32_t** | Hücrenin sıfır tabanlı sütun dizini. |

### Dönüş Değeri

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) metod


Belirtilen çalışma sayfasından, dizini ve Excel tarzı hücre adı (ör. "B2") kullanarak bir hücre alır.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının sıfır tabanlı dizini. |
| cellName | [System::String](../../../system/string/) | Excel tarzı hücre referansı (ör. "A1", "C5"). |

### Dönüş Değeri

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) metod


Excel tarzı hücre adı (ör. "B2") kullanarak belirtilen çalışma sayfasından bir hücre alır.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Çalışma sayfasının adı. |
| cellName | [System::String](../../../system/string/) | Excel tarzı hücre referansı (ör. "A1", "C5"). |

### Dönüş Değeri

Belirtilen konumdaki hücre.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IExcelDataCell](../../iexceldatacell/)
* Sınıf [IExcelDataWorkbook](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)