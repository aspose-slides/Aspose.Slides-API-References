---
title: get_FontsManager()
second_title: مرجع API Aspose.Slides برای C++
description: یک مدیر قلم‌ها را برمی‌گرداند. فقط-خواندنی IFontsManager.
type: docs
weight: 157
url: /fa/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() متد

مدیر قلم‌ها را برمی‌گرداند. فقط-خواندنی [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## ملاحظات

مثال زیر نشان می‌دهد چگونه می‌توان قلم‌های توکار را به PowerPoint [Presentation](../) افزود.
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

// ذخیرهٔ ارائه
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontsManager](../../ifontsmanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)