---
title: get_Value()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Excel सेल में निहित मान प्राप्त करता है। केवल पढ़ने योग्य System::Object."
type: docs
weight: 1
url: /hi/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() विधि


[Excel](../../) सेल में निहित मान प्राप्त करता है। केवल पढ़ने योग्य [System::Object](../../../system/object/)।

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [IExcelDataCell](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)