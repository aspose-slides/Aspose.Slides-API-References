---
title: get_Column()
second_title: Aspose.Slides for C++ API संदर्भ
description: कार्यपत्रक में उस कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। केवल-पढ़ने योग्य int32_t.
type: docs
weight: 40
url: /hi/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() विधि


कार्यपत्रक में उस कॉलम का शून्य-आधारित सूचकांक प्राप्त करता है जहाँ सेल स्थित है। केवल-पढ़ने योग्य **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## देखें

* क्लास [IExcelDataCell](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)