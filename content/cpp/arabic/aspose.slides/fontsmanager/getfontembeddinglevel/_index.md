---
title: GetFontEmbeddingLevel()
second_title: مرجع Aspose.Slides للغة C++
description: يحدد مستوى تضمين الخط من مصفوفة البايتات المحددة واسم الخط.
type: docs
weight: 144
url: /ar/aspose.slides/fontsmanager/getfontembeddinglevel/
---
## FontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) طريقة

يحدد مستوى تضمين الخط من مصفوفة البايتات المعطاة واسم الخط.

```cpp
Aspose::Slides::EmbeddingLevel Aspose::Slides::FontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايتات التي تحتوي على بيانات الخط. |
| fontName | [System::String](../../../system/string/) | اسم الخط. |

### قيمة الإرجاع

مستوى تضمين الخط المحدد.
## ملاحظات




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// Determine the embedding level of the font
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## انظر أيضًا

* تعداد [EmbeddingLevel](../../embeddinglevel/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [FontsManager](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)