---
title: get_Column()
second_title: Aspose.Slides for C++ API संदर्भ
description: सेल जिस वर्कशीट में स्थित है, वहाँ कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है। केवल-पढ़ने योग्य int32_t.
type: docs
weight: 40
url: /hi/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() विधि


सेल जिस वर्कशीट में स्थित है, वहाँ कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है। केवल पढ़ने योग्य **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## टिप्पणी


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## देखें

* क्लास [ExcelDataCell](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)