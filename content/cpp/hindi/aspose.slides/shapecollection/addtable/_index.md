---
title: AddTable()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नई टेबल बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।
type: docs
weight: 469
url: /hi/aspose.slides/shapecollection/addtable/
---
## ShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) विधि

एक नई टेबल बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | **float** | टेबल का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | टेबल का y-निर्देशांक, पॉइंट्स में। |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | डबल्स की एक सरणी जो टेबल के कॉलम की चौड़ाइयों को दर्शाती है, पॉइंट्स में। |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | डबल्स की एक सरणी जो टेबल की पंक्तियों की ऊँचाइयों को दर्शाती है, पॉइंट्स में। |

### रिटर्न मान

नया बनाया गया [ITable](../../itable/)।

## टिप्पणियाँ

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint में टेबल कैसे जोड़ें [Presentation](../../presentation/)।

```cpp
// PPTX फ़ाइल का प्रतिनिधित्व करने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>();
// पहली स्लाइड तक पहुंचें
auto slide = pres->get_Slides()->idx_get(0);
// कॉलम की चौड़ाइयों और पंक्तियों की ऊँचाइयों को परिभाषित करें
System::ArrayPtr<double> dblCols = System::MakeArray<double>({50, 50, 50});
System::ArrayPtr<double> dblRows = System::MakeArray<double>({50, 30, 30, 30, 30});
// स्लाइड में टेबल आकार जोड़ें
System::SharedPtr<ITable> table = slide->get_Shapes()->AddTable(100.0f, 50.0f, dblCols, dblRows);
// प्रत्येक सेल के लिए बॉर्डर फ़ॉर्मेट सेट करें
for (int32_t row = 0; row < table->get_Rows()->get_Count(); row++)
{
    auto currentRow = table->get_Rows()->idx_get(row);
    for (int32_t col = 0; col < currentRow->get_Count(); col++)
    {
        auto cell = currentRow->idx_get(col);
        auto cellFormat = cell->get_CellFormat();
        cellFormat->get_BorderTop()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderTop()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderTop()->set_Width(5);
        cellFormat->get_BorderBottom()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderBottom()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderBottom()->set_Width(5);
        cellFormat->get_BorderLeft()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderLeft()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderLeft()->set_Width(5);
        cellFormat->get_BorderRight()->get_FillFormat()->set_FillType(FillType::Solid);
        cellFormat->get_BorderRight()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
        cellFormat->get_BorderRight()->set_Width(5);
    }
}

// पंक्ति 1 के सेल 1 और 2 को मिलाएँ
table->MergeCells(table->get_Rows()->idx_get(0)->idx_get(0), table->get_Rows()->idx_get(1)->idx_get(1), false);
// मर्ज किए गए सेल में टेक्स्ट जोड़ें
table->get_Rows()->idx_get(0)->idx_get(0)->get_TextFrame()->set_Text(u"Merged Cells");
// PPTX को डिस्क पर सहेजें
pres->Save(u"table.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [ITable](../../itable/)
* क्लास [ShapeCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)