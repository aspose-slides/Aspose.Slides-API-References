---
title: get_Value()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: Excel सेल में सम्मिलित मान प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() मेथड


[Excel](../../) सेल में सम्मिलित मान प्राप्त करता है।

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [ExcelDataCell](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)