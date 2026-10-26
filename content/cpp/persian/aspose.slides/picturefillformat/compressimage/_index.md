---
title: CompressImage()
second_title: مرجع API Aspose.Slides برای C++
description: تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌طور اختیاری، مناطق برش‌خورده را نیز حذف می‌کند.
type: docs
weight: 443
url: /fa/aspose.slides/picturefillformat/compressimage/
---
## PictureFillFormat::CompressImage(bool, Export::PicturesCompression) متد

تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌طور اختیاری، مناطق برش‌خورده را نیز حذف می‌کند.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, Export::PicturesCompression resolution) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | اگر مقدار true باشد، این متد مناطق برش‌خورده تصویر را حذف می‌کند و ممکن است اندازه آن بیشتر کاهش یابد. |
| resolution | [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) | وضوح هدف برای فشرده‌سازی که به عنوان مقداری از enum [Export::PicturesCompression](../../../aspose.slides.export/picturescompression/) مشخص می‌شود. |

### مقدار بازگشت

یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شد یا خیر. باز می‌گرداند ****true****

## نکات

این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

اگر تصویر تغییر اندازه یا برش خورده باشد، در غیر اینصورت ****false****.

. 

مثال زیر نشان می‌دهد چگونه می‌توان از متد **CompressImage** برای کاهش اندازه تصویر در یک ارائه با تنظیم وضوح هدف و حذف مناطق برش‌خورده استفاده کرد: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));
// تصویر را با وضوح هدف 150 DPI (وضوح وب) فشرده کنید و مناطق برش‌خورده را حذف کنید
bool result = picFrame->get_PictureFormat()->CompressImage(true, PicturesCompression::Dpi150);
```

## PictureFillFormat::CompressImage(bool, float) متد

تصویر را با کاهش اندازه آن بر اساس اندازه شکل و وضوح مشخص‌شده فشرده می‌کند. به‌طور اختیاری، مناطق برش‌خورده را نیز حذف می‌کند.

```cpp
bool Aspose::Slides::PictureFillFormat::CompressImage(bool deleteCroppedAreasOfImage, float resolution) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| deleteCroppedAreasOfImage | **bool** | اگر مقدار true باشد، این متد مناطق برش‌خورده تصویر را حذف می‌کند و ممکن است اندازه آن بیشتر کاهش یابد. |
| resolution | **float** | وضوح هدف به DPI. این مقدار باید مثبت باشد و تعیین می‌کند تصویر چگونه تغییر اندازه می‌یابد. |

### مقدار بازگشت

یک **bool** که نشان می‌دهد آیا تصویر با موفقیت فشرده شد یا خیر. باز می‌گرداند ****true****

## نکات

این متد اندازه و وضوح تصویر را مشابه ویژگی "Picture Format -> Compress Pictures" در PowerPoint تغییر می‌دهد.

اگر تصویر تغییر اندازه یا برش خورده باشد، در غیر اینصورت ****false****.

. 

مثال زیر نشان می‌دهد چگونه می‌توان از متد **CompressImage** برای کاهش اندازه تصویر در یک ارائه با تنظیم وضوح هدف و حذف مناطق برش‌خورده استفاده کرد: 
```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// دریافت PictureFrame
System::SharedPtr<IPictureFrame> picFrame = System::AsCast<IPictureFrame>(slide->get_Shape(0));

// تصویر را با وضوح هدف 150 DPI (وضوح وب) فشرده کنید و مناطق برش‌خورده را حذف کنید
bool result = picFrame->get_PictureFormat()->CompressImage(true, 150.0f); // وضوح وب
```

## موارد مرتبط

* enum [PicturesCompression](../../../aspose.slides.export/picturescompression/)
* کلاس [PictureFillFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)