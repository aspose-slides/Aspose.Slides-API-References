---
title: GetFontBytes()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: تسترجع مصفوفة البايتات التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.
type: docs
weight: 131
url: /ar/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) طريقة

تسترجع مصفوفة البايتات التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | كائن بيانات الخط الذي يحتوي على المعلومات حول الخط [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | نمط الخط الذي يجب استرجاع البيانات له [FontStyleType](../../fontstyletype/). |

### القيمة المرجعة

مصفوفة من البايتات تحتوي على بيانات الخط للنمط المحدد. إذا لم يتم العثور على بيانات الخط أو النمط، تُرجع null.

## ملاحظات




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## انظر أيضًا

* تعداد [FontStyleType](../../fontstyletype/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IFontData](../../ifontdata/)
* فئة [FontsManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)