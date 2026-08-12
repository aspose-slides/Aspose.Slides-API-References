---
title: SetMacroHyperlinkClick()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्लिक पर मैक्रो हाइपरलिंक सेट करें।
type: docs
weight: 79
url: /hi/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) method


क्लिक पर मैक्रो हाइपरलिंक सेट करें।

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | मैक्रो का नाम |

### रिटर्न मान

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## टिप्पणियाँ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```


## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IHyperlink](../../ihyperlink/)
* क्लास [String](../../../system/string/)
* क्लास [HyperlinkManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)