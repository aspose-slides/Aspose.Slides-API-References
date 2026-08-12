---
title: get_Name()
second_title: Aspose.Slides for C++ API संदर्भ
description: "चार्ट डेटा सेल का नाम प्राप्त करता है। केवल पढ़ने योग्य System::String."
type: docs
weight: 14
url: /hi/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() विधि


चार्ट डेटा सेल का नाम प्राप्त करता है। केवल पढ़ने योग्य [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [IExcelDataCell](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)