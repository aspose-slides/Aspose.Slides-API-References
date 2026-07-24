---
title: GetWorksheetNames()
second_title: Aspose.Slides for C++ API Referansı
description: Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını getirir.
type: docs
weight: 40
url: /tr/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metodu


[Excel](../../) çalışma kitabında bulunan tüm çalışma sayfalarının adlarını getirir.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Dönüş Değeri

Çalışma sayfası adlarının bir listesi
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)