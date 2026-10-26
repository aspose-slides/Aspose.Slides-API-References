---
title: GetCells()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen formülle eşleşen hücreleri çalışma kitabından içeren bir koleksiyon alır.
type: docs
weight: 1
url: /tr/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) metodu


Belirtilen formülle eşleşen hücreleri içeren bir koleksiyon döndürür.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Hedef hücreleri belirlemek için kullanılan bir formül veya aralık ifadesi (ör., "Sheet1!A1:B3"). |
| skipHiddenCells | **bool** | Eğer **true**, gizli hücreler (ör., gizli satırlarda veya sütunlarda) sonuçtan dışlanır. |

### Return Value

Belirtilen formülle eşleşen hücrelerin salt okunur bir listesi.
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## See Also

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Sınıf [IExcelDataCell](../../iexceldatacell/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExcelDataWorkbook](../)
* Ad Alanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)