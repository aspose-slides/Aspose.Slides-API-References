---
title: get_Value()
second_title: Aspose.Slides for C++ API Referansı
description: "Excel hücresinde bulunan değeri alır. Yalnızca okuma System::Object."
type: docs
weight: 1
url: /tr/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() method


[Excel](../../) hücresinde bulunan değeri alır. Yalnızca okuma [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```


## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [IExcelDataCell](../)
* AdAlanı [Aspose::Slides::Excel](../../)
* Kütüphane [Aspose.Slides](../../../)