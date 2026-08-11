---
title: GetFontEmbeddingLevel()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط.
type: docs
weight: 144
url: /ar/aspose.slides/ifontsmanager/getfontembeddinglevel/
---
## IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr\<uint8_t\>, System::String) طريقة

يحدد مستوى تضمين الخط من مصفوفة البايت المعطاة واسم الخط.

```cpp
virtual EmbeddingLevel Aspose::Slides::IFontsManager::GetFontEmbeddingLevel(System::ArrayPtr<uint8_t> fontBytes, System::String fontName)=0
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| fontBytes | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي تحتوي على بيانات الخط. |
| fontName | [System::String](../../../system/string/) | اسم الخط. |

### قيمة الإرجاع

مستوى تضمين الخط المحدد.

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// استرجاع جميع الخطوط المستخدمة في العرض التقديمي
System::ArrayPtr<System::SharedPtr<IFontData>> fontDatas = pres->get_FontsManager()->GetFonts();

// الحصول على مصفوفة البايت التي تمثل النمط العادي لأول خط في العرض التقديمي
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fontDatas[0], System::Drawing::FontStyle::Regular);

// تحديد مستوى تضمين الخط
EmbeddingLevel embeddingLevel = pres->get_FontsManager()->GetFontEmbeddingLevel(bytes, fontDatas[0]->get_FontName());
```

## انظر أيضًا

* تعداد [EmbeddingLevel](../../embeddinglevel/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [IFontsManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)