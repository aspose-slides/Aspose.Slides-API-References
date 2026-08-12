---
title: AddMathShape()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: गणितीय सामग्री को होस्ट करने के लिए एक नया आयताकार ऑटो शैप बनाता है और इसे शैप संग्रह के अंत में जोड़ता है।
type: docs
weight: 365
url: /hi/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) मेथड

गणितीय सामग्री को होस्ट करने के लिए एक नया आयताकार ऑटो शेप बनाता है और इसे शेप कलेक्शन के अंत में जोड़ता है।

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| x | **float** | आकार के फ़्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | आकार के फ़्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | आकार के फ़्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | आकार के फ़्रेम की ऊँचाई, पॉइंट्स में। |

### रिटर्न वैल्यू

नया बनाया गया [IAutoShape](../../iautoshape/).

## टिप्पणियाँ

निम्न उदाहरण दिखाता है कि PowerPoint में गणितीय समीकरण कैसे जोड़ा जाए [Presentation](../../presentation/)। 
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAutoShape](../../iautoshape/)
* क्लास [ShapeCollection](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)