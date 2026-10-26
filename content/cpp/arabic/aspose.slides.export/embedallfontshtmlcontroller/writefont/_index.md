---
title: WriteFont()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب البيانات بصيغة base64 داخل مستند HTML نفسه
type: docs
weight: 105
url: /ar/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) method

يكتب البيانات بصيغة base64 داخل مستند HTML نفسه

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | HTML generator |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Font to be serialized |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Substituted font (if font substitution occured), null otherwise |
| fontStyle | [System::String](../../../system/string/) | Font style |
| fontWeight | [System::String](../../../system/string/) | Font weight |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Font data |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IHtmlGenerator](../../ihtmlgenerator/)
* فئة [IFontData](../../../aspose.slides/ifontdata/)
* فئة [String](../../../system/string/)
* فئة [EmbedAllFontsHtmlController](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)