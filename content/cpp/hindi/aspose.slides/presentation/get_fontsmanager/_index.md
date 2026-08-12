---
title: get_FontsManager()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ॉन्ट्स मैनेज़र को लौटाता है। केवल-पढ़ने योग्य IFontsManager.
type: docs
weight: 157
url: /hi/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() विधि

फ़ॉन्ट्स मैनेज़र को लौटाता है। केवल-पढ़ने योग्य [IFontsManager](../../ifontsmanager/)।

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## टिप्पणियाँ

निम्नलिखित उदाहरण दर्शाता है कि PowerPoint [Presentation](../) में एम्बेडेड फ़ॉन्ट्स कैसे जोड़ें।

```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IFontsManager](../../ifontsmanager/)
* क्लास [Presentation](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)