---
title: set_DocumentLevelFontSources()
second_title: مرجع API Aspose.Slides برای C++
description: منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند
type: docs
weight: 222
url: /fa/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) متد

منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند.

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## توضیحات

مثال زیر نشان می‌دهد چگونه می‌توان فونت‌های سفارشی مورد استفاده در PowerPoint [Presentation](../../presentation/) را مشخص کرد.
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// کار با ارائه
// CustomFont1، CustomFont2 به همراه فونت‌های موجود در پوشه‌های assets\fonts و global\fonts و زیرپوشه‌های آن‌ها برای ارائه در دسترس هستند
```

## نگاهی دیگر

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontSources](../../ifontsources/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)