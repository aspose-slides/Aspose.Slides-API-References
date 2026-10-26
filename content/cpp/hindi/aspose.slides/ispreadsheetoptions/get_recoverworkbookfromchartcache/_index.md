---
title: get_RecoverWorkbookFromChartCache()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो उसे चार्ट कैश से पुनर्प्राप्त किया जाएगा।
type: docs
weight: 27
url: /hi/aspose.slides/ispreadsheetoptions/get_recoverworkbookfromchartcache/
---
## ISpreadsheetOptions::get_RecoverWorkbookFromChartCache() विधि

यदि चार्ट के लिए डेटा स्रोत एक बाहरी वर्कबुक है और वह उपलब्ध नहीं है, तो इसे चार्ट कैश से पुनर्प्राप्त किया जाएगा।

```cpp
virtual bool Aspose::Slides::ISpreadsheetOptions::get_RecoverWorkbookFromChartCache()=0
```

## टिप्पणी

उदाहरण:
```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->set_SpreadsheetOptions(System::MakeObject<SpreadsheetOptions>());
loadOptions->get_SpreadsheetOptions()->set_RecoverWorkbookFromChartCache(true);

auto pres = MakeObject<Presentation>(u"Presentation.pptx", loadOptions);
auto chart = AsCast<Aspose::Slides::Charts::IChart>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto recoveredWorkbook = chart->get_ChartData()->get_ChartDataWorkbook();
```

## देखें भी

* क्लास [ISpreadsheetOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)