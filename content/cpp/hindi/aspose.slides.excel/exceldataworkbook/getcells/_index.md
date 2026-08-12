---
title: GetCells()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्कबुक से निर्दिष्ट फार्मूले से मेल खाने वाले सेल्स का संग्रह पुनः प्राप्त करता है।
type: docs
weight: 14
url: /hi/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) method

वर्कबुक से निर्दिष्ट फार्मूले से मेल खाने वाले सेल्स का संग्रह पुनः प्राप्त करता है।

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### तर्क

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | लक्ष्य सेल्स की पहचान के लिए उपयोग किया गया फार्मूला या रेंज अभिव्यक्ति (जैसे, "Sheet1!A1:B3")। |
| skipHiddenCells | **bool** | यदि **true** है, तो छिपे हुए सेल्स (जैसे, छिपी पंक्तियों या स्तंभों में) परिणाम में शामिल नहीं किए जाएंगे। |

## वापसी मान

एक पढ़ने-के-लिए-केवल सूची जिसमें निर्दिष्ट फार्मूले से मेल खाने वाले सेल्स होते हैं।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* क्लास [IExcelDataCell](../../iexceldatacell/)
* क्लास [String](../../../system/string/)
* क्लास [ExcelDataWorkbook](../)
* नेमस्पेस [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)