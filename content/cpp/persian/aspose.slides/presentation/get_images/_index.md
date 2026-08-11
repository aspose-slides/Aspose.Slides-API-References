---
title: get_Images()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعهٔ تمام تصاویر در ارائه را برمی‌گرداند. فقط خواندنی IImageCollection.
type: docs
weight: 209
url: /fa/aspose.slides/presentation/get_images/
---
## Presentation::get_Images() متد

مجموعهٔ تمام تصاویر در ارائه را برمی‌گرداند. فقط خواندنی [IImageCollection](../../iimagecollection/).

```cpp
System::SharedPtr<IImageCollection> Aspose::Slides::Presentation::get_Images() override
```

## توضیحات

مثال‌های زیر نشان می‌دهد چگونه تصویر را به‌عنوان BLOB در PowerPoint [Presentation](../) اضافه کنید.
```cpp
System::String pathToLargeImage = u"large_image.jpg";
// یک ارائهٔ جدید ایجاد می‌کند که تصویر به آن اضافه می‌شود.
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToLargeImage, System::IO::FileMode::Open);

// بیایید تصویر را به ارائه اضافه کنیم - رفتار KeepLocked را انتخاب می‌کنیم چون ما
// قصد دسترسی به فایل "largeImage.png" را نداریم.
auto img = pres->get_Images()->AddImage(fileStream, LoadingStreamBehavior::KeepLocked);
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 0.0f, 0.0f, 300.0f, 200.0f, img);
// ارائه را ذخیره می‌کند. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
// در طول دورهٔ حیات شی pres کم می‌ماند
pres->Save(u"presentationWithLargeImage.pptx", SaveFormat::Pptx);
```
 مثال‌های زیر یک پیوند به تصویر در PowerPoint [Presentation](../) اضافه می‌کند.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// افزودن تصویر به ارائه
auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
// Creates picture frame on slide 1 based on previously added image
auto pictureFrame = slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pictureFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
pictureFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IImageCollection](../../iimagecollection/)
* کلاس [Presentation](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)