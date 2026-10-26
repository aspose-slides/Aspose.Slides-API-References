---
title: GetCells()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen formülle eşleşen hücrelerden oluşan bir koleksiyonu çalışma kitabından alır.
type: docs
weight: 14
url: /tr/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) metodu

Belirtilen formülle eşleşen hücrelerin bir koleksiyonunu çalışma kitabından alır.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Hedef hücreleri belirlemek için kullanılan bir formül veya aralık ifadesi (ör. \"Sheet1!A1:B3\"). |
| skipHiddenCells | **bool** | **true** olduğunda, gizli hücreler (ör. gizli satır veya sütunlardaki hücreler) sonuçtan dışlanacaktır. |

### Return Value

Belirtilen formülle eşleşen hücrelerin salt okunur bir listesi.

## Açıklamalar

Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Sınıf [IExcelDataCell](../../iexceldatacell/)
* Sınıf [String](../../../system/string/)
* Sınıf [ExcelDataWorkbook](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)