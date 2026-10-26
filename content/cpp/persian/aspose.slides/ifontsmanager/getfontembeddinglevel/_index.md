---
title: GetFontEmbeddingLevel()
second_title: Aspose.Slides برای مرجع API C++
description: سطح جاسازی یک قلم را بر اساس آرایه بایتی داده‌شده و نام قلم تعیین می‌کند.
type: docs
weight: 144
url: /fa/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) متد

سطح جاسازی یک قلم را بر اساس آرایه بایت داده‌شده و نام قلم تعیین می‌کند.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که شامل داده‌های قلم است. |
| fontName | [System::String](../../../system/string/) | نام قلم. |

### مقدار بازگشتی

سطح جاسازی قلم مشخص‌شده.

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

## موارد مرتبط

* Enum [EmbeddingLevel](../../embeddinglevel/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)