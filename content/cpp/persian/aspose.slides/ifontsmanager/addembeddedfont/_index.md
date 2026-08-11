---
title: AddEmbeddedFont()
second_title: مرجع API Aspose.Slides برای C++
description: فونت تعبیه‌شده را اضافه می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides/ifontsmanager/addembeddedfont/
---
## IFontsManager::AddEmbeddedFont(System::SharedPtr\<IFontData\>, Export::EmbedFontCharacters) متد

فونت تعبیه‌شده را اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::SharedPtr<IFontData> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | شی داده فونت [IFontData](../../ifontdata/) |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | قانون فونت تعبیه‌شده [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## توضیحات

در نظر داشته باشید هنگام کپی کردن هر فونتی، اکثر فونت‌ها دارای حق کپی‌رایت هستند. ابتدا مجوز یک فونت را پیدا کنید و بررسی کنید که آیا می‌توان آن را به‌صورت آزاد به ماشین دیگری منتقل کرد.

## IFontsManager::AddEmbeddedFont(System::ArrayPtr\<uint8_t\>, Export::EmbedFontCharacters) متد

فونت تعبیه‌شده را اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IFontsManager::AddEmbeddedFont(System::ArrayPtr<uint8_t> fontData, Export::EmbedFontCharacters embedFontRule)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده‌های فونت **uint8_t**[] |
| embedFontRule | [Export::EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) | قانون فونت تعبیه‌شده [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/) |

## توضیحات

در نظر داشته باشید هنگام افزودن هر فونتی، اکثر فونت‌ها دارای حق کپی‌رایت هستند. ابتدا مجوز یک فونت را پیدا کنید و بررسی کنید که آیا می‌توان آن را به‌صورت آزاد به ماشین دیگری منتقل کرد.

## مراجع مرتبط

* Enum [EmbedFontCharacters](../../../aspose.slides.export/embedfontcharacters/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)