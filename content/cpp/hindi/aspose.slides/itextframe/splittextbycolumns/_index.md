---
title: SplitTextByColumns()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: ITextFrame के टेक्स्ट कंटेंट को स्ट्रिंग्स की एरे में विभाजित करता है, जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम से संबंधित होता है।
type: docs
weight: 118
url: /hi/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() विधि

[ITextFrame](../) के टेक्स्ट कंटेंट को स्ट्रिंग्स की एरे में विभाजित करता है, 
 जहाँ प्रत्येक तत्व फ्रेम के भीतर एक अलग टेक्स्ट कॉलम से संबंधित है।

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### Return Value

स्ट्रिंग्स की एक एरे, जहाँ प्रत्येक स्ट्रिंग किसी विशिष्ट कॉलम के टेक्स्ट कंटेंट का प्रतिनिधित्व करती है 
 [ITextFrame](../) में।

## टिप्पणी

यदि टेक्स्ट फ्रेम में कई कॉलम नहीं हैं, तो लौटाई गई एरे में केवल एक तत्व होगा 
 जिसमें पूर्ण टेक्स्ट शामिल होगा। 
 खाली कॉलम एरे में खाली स्ट्रिंग्स के रूप में दर्शाए जाएंगे। 
 निम्न उदाहरण दिखाता है कि [ITextFrame::SplitTextByColumns](./) का उपयोग कैसे करें: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// स्लाइड पर पहला आकार प्राप्त करें और इसे ITextFrame में कास्ट करें
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// टेक्स्ट फ्रेम की सामग्री को कॉलम में विभाजित करें
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// प्रत्येक कॉलम के टेक्स्ट को कंसोल में प्रिंट करें
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)