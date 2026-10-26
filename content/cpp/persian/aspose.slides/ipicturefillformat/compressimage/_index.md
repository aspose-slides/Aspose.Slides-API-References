---
title: CompressImage()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، نواحی برش‌خورده را نیز حذف می‌نماید.
type: docs
weight: 443
url: /fa/aspose.slides/ipicturefillformat/compressimage/
---
## IPictureFillFormat::CompressImage(bool, Export::PicturesCompression) method


تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، نواحی برش‌خورده را نیز حذف می‌نماید.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | اگر مقدار true باشد، متد نواحی برش‌خورده تصویر را حذف می‌کند و ممکن است اندازه آن بیشتر کاهش یابد. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | وضوح هدف برای فشرده‌سازی که به عنوان مقداری از enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) مشخص می‌شود. |

### مقدار بازگشت

یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است. مقدار برگشتی ****true****

## توضیحات

این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

اگر تصویر تغییر اندازه یا برش خورده باشد، در غیر این صورت ****false****

. 

مثال زیر نشان می‌دهد چگونه می‌توان از متد **CompressImage** برای کاهش اندازه یک تصویر در یک ارائه با تعیین وضوح هدف و حذف نواحی برش‌خورده استفاده کرد: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// تصویر را با وضوح هدف 150 DPI (وضوح وب) فشرده کنید و نواحی برش‌خورده را حذف کنید
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## IPictureFillFormat::CompressImage(bool, float) method


تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌صورت اختیاری، نواحی برش‌خورده را نیز حذف می‌نماید.

```cpp
virtual bool Aspose::Slides::IPictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | اگر مقدار true باشد، متد نواحی برش‌خورده تصویر را حذف می‌کند و ممکن است اندازه آن بیشتر کاهش یابد. |
| resolution | **float** | وضوح هدف بر حسب DPI. این مقدار باید مثبت باشد و تعیین می‌کند تصویر چگونه تغییر اندازه خواهد یافت. |

### مقدار بازگشت

یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شده است. مقدار برگشتی ****true****

## توضیحات

این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

اگر تصویر تغییر اندازه یا برش خورده باشد، در غیر این صورت ****false****

. 

مثال زیر نشان می‌دهد چگونه می‌توان از متد **CompressImage** برای کاهش اندازه یک تصویر در یک ارائه با تعیین وضوح هدف و حذف نواحی برش‌خورده استفاده کرد: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// کادر تصویر را دریافت می‌کند
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// تصویر را با وضوح هدف 150 DPI (وضوح وب) فشرده کنید و نواحی برش‌خورده را حذف کنید
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // وضوح وب
```

## موارد مرتبط

* Enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* Class [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)