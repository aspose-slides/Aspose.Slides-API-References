---
title: WriteFont()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌ها را به صورت base64 در خود سند HTML می‌نویسد
type: docs
weight: 105
url: /fa/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) متد


داده‌ها را به صورت base64 در خود سند HTML می‌نویسد

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | مولد HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | فونت برای سریال‌سازی |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | فونت جایگزین (اگر تعویض فونت رخ داده باشد)، در غیر این صورت null |
| fontStyle | [System::String](../../../system/string/) | سبک فونت |
| fontWeight | [System::String](../../../system/string/) | وزن فونت |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | داده فونت |

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [IHtmlGenerator](../../ihtmlgenerator/)
* کلاس [IFontData](../../../aspose.slides/ifontdata/)
* کلاس [String](../../../system/string/)
* کلاس [EmbedAllFontsHtmlController](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)