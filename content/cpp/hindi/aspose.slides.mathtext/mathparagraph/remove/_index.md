---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह से एक विशिष्ट ऑब्जेक्ट की पहली उपस्थिति को हटाता है/>.
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) विधि

संग्रह से एक विशिष्ट ऑब्जेक्ट का पहला प्रकट होना हटाता है/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | संग्रह से हटाने के लिए ऑब्जेक्ट। |

### रिटर्न वैल्यू

true यदि *mathBlock* संग्रह से सफलतापूर्वक हटाया गया; अन्यथा false। यह विधि false भी लौटाती है यदि *mathBlock* मूल संग्रह में नहीं मिला/>.

## टिप्पणी

उदाहरण: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../../imathblock/)
* क्लास [MathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)