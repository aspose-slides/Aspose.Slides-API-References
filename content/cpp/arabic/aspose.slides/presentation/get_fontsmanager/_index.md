---
title: get_FontsManager()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد مدير الخطوط. للقراءة فقط IFontsManager.
type: docs
weight: 157
url: /ar/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() طريقة

يعيد مدير الخطوط. للقراءة فقط [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## ملاحظات

المثال التالي يوضح كيفية إضافة خطوط مضمنة إلى PowerPoint [Presentation](../). ```cpp
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

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontsManager](../../ifontsmanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)