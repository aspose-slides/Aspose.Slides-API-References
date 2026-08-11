---
title: GetFontBytes()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.
type: docs
weight: 131
url: /ar/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) طريقة

يسترجع مصفوفة البايت التي تمثل بيانات الخط لنمط خط محدد وبيانات الخط.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | كائن بيانات الخط الذي يحتوي على المعلومات حول الخط [IFontData](../../ifontdata/). |
| fontStyle | [FontStyleType](../../fontstyletype/) | نمط الخط الذي يجب استرجاع البيانات له [FontStyleType](../../fontstyletype/). |

### قيمة الإرجاع

مصفوفة بايت تحتوي على بيانات الخط للنمط المحدد. إذا لم يتم العثور على بيانات الخط أو النمط، تُرجع null.
## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## انظر أيضًا

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)