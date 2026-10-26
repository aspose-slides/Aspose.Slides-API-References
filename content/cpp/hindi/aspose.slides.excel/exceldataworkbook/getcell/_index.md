---
title: GetCell()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट कार्यपत्रक से उसके सूचकांक और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।
type: docs
weight: 27
url: /hi/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) विधि

निर्दिष्ट कार्यपत्रक से उसके सूचकांक और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | कार्यपत्रक का शून्य-आधारित सूचकांक। |
| row | **int32_t** | सेल की शून्य-आधारित पंक्ति सूचकांक। |
| column | **int32_t** | सेल की शून्य-आधारित स्तंभ सूचकांक। |

### रिटर्न मान

निर्दिष्ट स्थान पर सेल।

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) विधि

निर्दिष्ट कार्यपत्रक से उसके नाम और सेल निर्देशांक का उपयोग करके एक सेल प्राप्त करता है।

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | कार्यपत्रक का नाम। |
| row | **int32_t** | सेल की शून्य-आधारित पंक्ति सूचकांक। |
| column | **int32_t** | सेल की शून्य-आधारित स्तंभ सूचकांक। |

### रिटर्न मान

निर्दिष्ट स्थान पर सेल।

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) विधि

निर्दिष्ट कार्यपत्रक से उसके सूचकांक और Excel-शैली के सेल नाम (जैसे "B2") का उपयोग करके एक सेल प्राप्त करता है।

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | कार्यपत्रक का शून्य-आधारित सूचकांक। |
| cellName | [System::String](../../../system/string/) | Excel-शैली का सेल संदर्भ (जैसे "A1", "C5")। |

### रिटर्न मान

निर्दिष्ट स्थान पर सेल।

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) विधि

निर्दिष्ट कार्यपत्रक से Excel-शैली के सेल नाम (जैसे "B2") का उपयोग करके एक सेल प्राप्त करता है।

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | कार्यपत्रक का नाम। |
| cellName | [System::String](../../../system/string/) | Excel-शैली का सेल संदर्भ (जैसे "A1", "C5")। |

### रिटर्न मान

निर्दिष्ट स्थान पर सेल।

## टिप्पणियाँ

उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [ExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)