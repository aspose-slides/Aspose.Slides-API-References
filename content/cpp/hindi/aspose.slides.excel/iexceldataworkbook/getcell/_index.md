---
title: GetCell()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट कार्यपत्रक से उसकी अनुक्रमणिका और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

निर्दिष्ट कार्यपत्रक से उसकी अनुक्रमणिका और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | **int32_t** | कार्यपत्रक का शून्य-आधारित अनुक्रमणिका। |
| row | **int32_t** | सेल की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | **int32_t** | सेल की शून्य-आधारित स्तंभ अनुक्रमणिका। |

### रिटर्न वैल्यू

निर्दिष्ट स्थान पर सेल।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

निर्दिष्ट कार्यपत्रक से इसका नाम और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | कार्यपत्रक का नाम। |
| row | **int32_t** | सेल की शून्य-आधारित पंक्ति अनुक्रमणिका। |
| column | **int32_t** | सेल की शून्य-आधारित स्तंभ अनुक्रमणिका। |

### रिटर्न वैल्यू

निर्दिष्ट स्थान पर सेल।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) method

निर्दिष्ट कार्यपत्रक से इसकी अनुक्रमणिका और एक्सेल-शैली का सेल नाम (जैसे "B2") का उपयोग करके एक सेल प्राप्त करता है।

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetIndex | **int32_t** | कार्यपत्रक का शून्य-आधारित अनुक्रमणिका। |
| cellName | [System::String](../../../system/string/) | एक्सेल-शैली का सेल संदर्भ (जैसे "A1", "C5")। |

### रिटर्न वैल्यू

निर्दिष्ट स्थान पर सेल।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, System::String) method

निर्दिष्ट कार्यपत्रक से एक्सेल-शैली का सेल नाम (जैसे "B2") का उपयोग करके एक सेल प्राप्त करता है।

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | कार्यपत्रक का नाम। |
| cellName | [System::String](../../../system/string/) | एक्सेल-शैली का सेल संदर्भ (जैसे "A1", "C5")। |

### रिटर्न वैल्यू

निर्दिष्ट स्थान पर सेल।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IExcelDataCell](../../iexceldatacell/)
* क्लास [IExcelDataWorkbook](../)
* क्लास [String](../../../system/string/)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)