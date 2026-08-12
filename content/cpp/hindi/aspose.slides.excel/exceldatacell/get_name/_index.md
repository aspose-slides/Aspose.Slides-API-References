---
title: get_Name()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: चार्ट डेटा सेल का नाम प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() विधि


चार्ट डेटा सेल का नाम प्राप्त करता है।

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## और देखें

* क्लास [String](../../../system/string/)
* क्लास [ExcelDataCell](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)