---
title: get_Row()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: सेल जहाँ स्थित है, उस कार्यपत्र में पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है। केवल-पढ़ने योग्य int32_t.
type: docs
weight: 27
url: /hi/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() method


सेल जहाँ स्थित है, उस वर्कशीट में पंक्ति का शून्य-आधारित सूचकांक प्राप्त करता है। केवल-पढ़ने योग्य **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## संबंधित देखें

* क्लास [ExcelDataCell](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)