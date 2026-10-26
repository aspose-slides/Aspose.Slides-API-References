---
title: GetCell()
second_title: Aspose.Slides for C++ API Referansı
description: Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır
type: docs
weight: 27
url: /tr/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) yöntemi

Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Çalışma sayfasının adı. |
| row | **int32_t** | Satır. |
| column | **int32_t** | Sütun. |

### Dönüş Değeri

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) yöntemi


Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının dizini. |
| row | **int32_t** | Satır. |
| column | **int32_t** | Sütun. |

### Dönüş Değeri

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) yöntemi


Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının dizini. |
| cellName | [System::String](../../../system/string/) | Hücrenin adı. |

### Dönüş Değeri

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) yöntemi


Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının dizini. |
| cellName | [System::String](../../../system/string/) | Hücrenin adı. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

### Dönüş Değeri

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) yöntemi


Grafik serileri veya kategorileri için kullanılabilecek hücreyi alır

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Çalışma sayfasının dizini. |
| row | **int32_t** | Satır. |
| column | **int32_t** | Sütun. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Değer. |

### Dönüş Değeri

[Cell](../../../aspose.slides/cell/) object

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [String](../../../system/string/)
* Sınıf [ChartDataWorkbook](../)
* Sınıf [Object](../../../system/object/)
* AdAlanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)