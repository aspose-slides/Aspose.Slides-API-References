---
title: GetFontBytes()
second_title: مرجع API Aspose.Slides برای C++
description: آرایه بایت نمایانگر داده‌های قلم را برای سبک قلم مشخص و داده‌های قلم بازیابی می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/fontsmanager/getfontbytes/
---
## FontsManager::GetFontBytes(System::SharedPtr\<Aspose::Slides::IFontData\>, Aspose::Slides::FontStyleType) متد


آرایه بایت نمایانگر داده‌های قلم را برای سبک قلم مشخص و داده‌های قلم بازیابی می‌کند.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::FontsManager::GetFontBytes(System::SharedPtr<Aspose::Slides::IFontData> fontData, Aspose::Slides::FontStyleType fontStyle) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | شیء داده قلم حاوی اطلاعات دربارهٔ قلم [IFontData](../../ifontdata/). |
| fontStyle | [Aspose::Slides::FontStyleType](../../fontstyletype/) | سبک قلم که داده‌های آن باید بازیابی شود [FontStyleType](../../fontstyletype/). |

### مقدار بازگشت

آرایه بایتی شامل داده‌های قلم برای سبک قلم مشخص. اگر داده‌های قلم یا سبک یافت نشد، مقدار null برگردانده می‌شود.

## توضیحات


```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## برای اطلاعات بیشتر

* Enum [FontStyleType](../../fontstyletype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontData](../../ifontdata/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)