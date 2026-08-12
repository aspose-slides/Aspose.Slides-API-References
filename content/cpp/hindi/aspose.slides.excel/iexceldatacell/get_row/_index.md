---
title: get_Row()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: सेल जिस कार्यपत्र में स्थित है, उसकी पंक्ति का शून्य-आधारित अनुक्रमांक प्राप्त करता है। केवल-पठन int32_t।
type: docs
weight: 27
url: /hi/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() विधि

सेल जिस कार्यपत्र में स्थित है, उसकी पंक्ति का शून्य-आधारित अनुक्रमांक प्राप्त करता है। केवल-पठन **int32_t**।

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## टिप्पणी

उदाहरण:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## संबंधित देखें

* क्लास [IExcelDataCell](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)