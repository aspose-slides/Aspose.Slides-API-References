---
title: GetEffective()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: विरासत और तालिका शैलियों के लागू होने के साथ प्रभावी तालिका पंक्ति फ़ॉर्मेटिंग गुण प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() मेथड

विरासत और तालिका शैलियों के लागू होने के साथ प्रभावी तालिका पंक्ति फ़ॉर्मेटिंग गुण प्राप्त करता है।

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```

### रिटर्न वैल्यू

एक [IRowFormatEffectiveData](../../irowformateffectivedata/)।

## टिप्पणी

यह उदाहरण विभिन्न तालिका लॉजिक भागों के लिए प्रभावी फ़िल फ़ॉर्मेट प्राप्त करने को दर्शाता है। कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग हमेशा रो फ़ॉर्मेटिंग से अधिक प्राथमिकता रखती है, रो - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक। इसलिए अंततः CellFormatEffectiveData गुण हमेशा तालिका को ड्रॉ करने के लिए उपयोग किए जाते हैं। निम्नलिखित कोड केवल API का एक उदाहरण है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// आउटपुट और तुलना
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IRowFormatEffectiveData](../../irowformateffectivedata/)
* क्लास [RowFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)