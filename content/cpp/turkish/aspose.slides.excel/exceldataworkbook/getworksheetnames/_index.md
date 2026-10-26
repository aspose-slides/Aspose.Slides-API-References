---
title: GetWorksheetNames()
second_title: Aspose.Slides için C++ API Referansı
description: Excel çalışma kitabında bulunan tüm çalışma sayfalarının adlarını alır.
type: docs
weight: 53
url: /tr/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metodu


İçinde bulunan [Excel](../../) çalışma kitabındaki tüm çalışma sayfalarının adlarını alır.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Dönüş Değeri

Çalışma sayfası adlarının listesi
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

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IList](../../../system.collections.generic/ilist/)
* Sınıf [String](../../../system/string/)
* Sınıf [ExcelDataWorkbook](../)
* Ad alanı [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)