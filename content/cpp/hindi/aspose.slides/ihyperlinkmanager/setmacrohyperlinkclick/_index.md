---
title: SetMacroHyperlinkClick()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: क्लिक पर मैक्रो हाइपरलिंक सेट करें।
type: docs
weight: 79
url: /hi/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) मेथड

क्लिक पर मैक्रो हाइपरलिंक सेट करें।

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Name of the macro |

## रिटर्न वैल्यू

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## टिप्पणियाँ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IHyperlink](../../ihyperlink/)
* क्लास [String](../../../system/string/)
* क्लास [IHyperlinkManager](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)