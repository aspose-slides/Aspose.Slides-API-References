---
title: GetEffective()
second_title: Aspose.Slides का C++ API संदर्भ
description: विरासत और तालिका शैलियों को लागू करके प्रभावी तालिका कॉलम स्वरूपण गुण प्राप्त करता है।
type: docs
weight: 1
url: /hi/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() विधि

Gets effective table column formatting properties with inheritance and table styles applied.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```

### रिटर्न मान

एक [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## टिप्पणियाँ

यह उदाहरण विभिन्न तालिका तर्क भागों के लिए प्रभावी भराव स्वरूप प्राप्त करने को प्रदर्शित करता है। कृपया ध्यान दें कि सेल स्वरूपण हमेशा रो स्वरूपण से अधिक प्राथमिकता रखता है, रो - कॉलम से अधिक, कॉलम - पूरी तालिका से अधिक। इसलिए अंत में CellFormatEffectiveData गुण हमेशा तालिका को ड्रॉ करने के लिए प्रयुक्त होते हैं। नीचे दिया गया कोड केवल API का एक उदाहरण है। 
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* क्लास [ColumnFormat](../)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)