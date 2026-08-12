---
title: GetEffective()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: विरासत और टेबल शैलियों के लागू होने पर प्रभावी टेबल सेल फ़ॉर्मेटिंग गुण प्राप्त करता है।
type: docs
weight: 118
url: /hi/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() विधि

विरासत और टेबल शैली लागू होते हुए प्रभावी तालिका सेल फ़ॉर्मेटिंग गुण प्राप्त करता है.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```

### वापसी मान

एक [ICellFormatEffectiveData](../../icellformateffectivedata/).

## टिप्पणियाँ

यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी भराव स्वरूप प्राप्त करने का प्रदर्शन करता है। कृपया ध्यान दें कि सेल फ़ॉर्मेटिंग हमेशा पंक्ति फ़ॉर्मेटिंग से अधिक प्राथमिकता रखती है, पंक्ति - स्तंभ से अधिक, स्तंभ - पूरी तालिका से अधिक। इसलिए अंत में CellFormatEffectiveData गुण हमेशा तालिका को बनाने के लिए उपयोग किए जाते हैं। नीचे दिया गया कोड केवल API का एक उदाहरण है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// आउटपुट और तुलना
```

## और देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [ICellFormatEffectiveData](../../icellformateffectivedata/)
* क्लास [CellFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)