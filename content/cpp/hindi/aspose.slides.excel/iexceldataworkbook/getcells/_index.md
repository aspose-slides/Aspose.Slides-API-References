---
title: GetCells()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट फ़ॉर्मूला से मेल खाने वाले वर्कबुक से सेल्स का संग्रह प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) मेथड


निर्दिष्ट फ़ॉर्मूला से मेल खाने वाले वर्कबुक से सेल्स का एक संग्रह प्राप्त करता है।

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | लक्ष्य सेल्स की पहचान करने के लिए उपयोग किया जाने वाला फ़ॉर्मूला या रेंज एक्सप्रेशन (उदाहरण, "Sheet1!A1:B3"). |
| skipHiddenCells | **bool** | यदि **true**, छिपे हुए सेल्स (उदाहरण, छिपी पंक्तियों या स्तंभों में) परिणाम से बाहर कर दिए जाएंगे। |

### वापसी मान

निर्दिष्ट फ़ॉर्मूला से मेल खाने वाले सेल्स की एक केवल-रीड सूची।

## टिप्पणी



उदाहरण: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* क्लास [IExcelDataCell](../../iexceldatacell/)
* क्लास [String](../../../system/string/)
* क्लास [IExcelDataWorkbook](../)
* नामस्थान [Aspose::Slides::Excel](../../)
* लाइब्रेरी [Aspose.Slides](../../../)