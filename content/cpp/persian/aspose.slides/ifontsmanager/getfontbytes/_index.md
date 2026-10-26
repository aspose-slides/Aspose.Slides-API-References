---
title: GetFontBytes()
second_title: مرجع API Aspose.Slides برای C++
description: آرایه بایتی که نشانگر داده‌های قلم برای یک سبک قلم و داده‌های قلم مشخص است را بازیابی می‌کند.
type: docs
weight: 131
url: /fa/aspose.slides/ifontsmanager/getfontbytes/
---
## IFontsManager::GetFontBytes(System::SharedPtr\<IFontData\>, FontStyleType) method

آرایه بایتی که نشانگر داده‌های قلم برای یک سبک قلم و داده‌های قلم مشخص است را بازیابی می‌کند.

```cpp
virtual System::ArrayPtr<uint8_t> Aspose::Slides::IFontsManager::GetFontBytes(System::SharedPtr<IFontData> fontData, FontStyleType fontStyle)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontData | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | شیء داده‌های قلم که شامل اطلاعات مربوط به قلم [IFontData](../../ifontdata/) است. |
| fontStyle | [FontStyleType](../../fontstyletype/) | سبک قلم که داده‌های آن باید بازیابی شود [FontStyleType](../../fontstyletype/). |

### مقدار بازگشتی

آرایه بایتی که شامل داده‌های قلم برای سبک قلم مشخص شده است. اگر داده‌های قلم یا سبک یافت نشود، مقدار null برگردانده می‌شود.

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Retrieve all fonts used in the presentation
System::ArrayPtr<System::SharedPtr<IFontData>> fonts = pres->get_FontsManager()->GetFonts();

// Get the byte array representing the regular style of the first font in the presentation
System::ArrayPtr<uint8_t> bytes = pres->get_FontsManager()->GetFontBytes(fonts[0], FontStyleType::Regular);
```

## موارد مرتبط

* enum [FontStyleType](../../fontstyletype/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFontData](../../ifontdata/)
* کلاس [IFontsManager](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)