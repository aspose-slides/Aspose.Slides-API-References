---
title: LoadExternalFonts()
second_title: Aspose.Slides برای مرجع API C++
description: پوشه‌های اضافی برای جستجوی قلم‌ها اضافه می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) متد

پوشه‌های اضافی برای جستجوی قلم‌ها اضافه می‌کند.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | پوشه‌ها برای خواندن قلم‌های اضافی. |
## ملاحظات

مثال‌های زیر نشان می‌دهند چگونه قلم‌های سفارشی را از .TTF بارگذاری کنیم.
```cpp
// مسیر پوشه اسناد.
System::String dataDir = u"C:\\";

// پوشه‌ها برای جستجوی قلم‌ها
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// بارگذاری قلم‌های پوشه سفارشی
FontsLoader::LoadExternalFonts(folders);

// انجام برخی کارها و رندر ارائه/اسلایدها
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// پاک‌سازی کش قلم‌ها
FontsLoader::ClearCache();
```

## مراجع

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontsLoader](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)