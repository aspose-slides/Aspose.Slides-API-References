---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides برای C++ مرجع API
description: منابع فونت‌های خارجی که در ارائه استفاده می‌شوند را مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به اشتراک گذاشته نمی‌شوند
type: docs
weight: 209
url: /fa/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() متد

منابع فونت‌های خارجی که در ارائه استفاده می‌شوند را مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به اشتراک گذاشته نمی‌شوند.

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## توضیحات

مثال زیر نشان می‌دهد که چگونه می‌توان فونت‌های سفارشی مورد استفاده در PowerPoint [Presentation](../../presentation/) را مشخص کرد. 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// کار با ارائه
// CustomFont1، CustomFont2 و همچنین فونت‌های موجود در پوشه‌های assets\fonts و global\fonts و زیرپوشه‌های آن‌ها برای ارائه در دسترس هستند
```

## مراجع دیگر

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontSources](../../ifontsources/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)