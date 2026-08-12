---
title: set_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा।
type: docs
weight: 40
url: /hi/aspose.slides/ispreadsheetoptions/set_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool) मेथड


यदि चार्ट के लिए डेटा स्रोत एक बाहरी कार्यपुस्तिका है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा।

```cpp
virtual void Aspose::Slides::ISpreadsheetOptions::set_RecoverWorkbookFromChartCache(bool value)=0
```

## टिप्पणियाँ



उदाहरण: 
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## देखें

* क्लास [ISpreadsheetOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)