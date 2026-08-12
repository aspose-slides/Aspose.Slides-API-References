---
title: GetEffective()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: विरासत और लागू तालिका शैलियों के साथ प्रभावी तालिका स्वरूपण गुण प्राप्त करता है।
type: docs
weight: 40
url: /hi/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() मेथड


विरासत और तालिका शैलियों को लागू करके प्रभावी तालिका स्वरूपण गुण प्राप्त करता है।

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### रिटर्न वैल्यू

एक [ITableFormatEffectiveData](../../itableformateffectivedata/).
## टिप्पणी



यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी भराव स्वरूप प्राप्त करने को दर्शाता है। कृपया ध्यान दें कि सेल स्वरूपण की हमेशा पंक्ति स्वरूपण से उच्च प्राथमिकता होती है, पंक्ति की कॉलम से उच्च प्राथमिकता, कॉलम की पूरी तालिका से उच्च प्राथमिकता। इसलिए अंततः CellFormatEffectiveData गुण हमेशा तालिका को चित्रित करने के लिए उपयोग किए जाते हैं। निम्नलिखित कोड केवल API का एक उदाहरण है। 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ITableFormatEffectiveData](../../itableformateffectivedata/)
* क्लास [TableFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)