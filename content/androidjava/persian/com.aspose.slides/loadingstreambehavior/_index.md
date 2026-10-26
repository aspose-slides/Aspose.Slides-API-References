---
title: LoadingStreamBehavior
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: java.io.InputStream که به یک متد پاس داده می‌شود به عنوان یک شیء بزرگ باینری (BLOB) در نظر گرفته می‌شود؛ برای توضیح مراجعه کنید.
type: docs
url: /fa/com.aspose.slides/loadingstreambehavior/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream که به یک متد پاس داده می‌شود به عنوان یک شیء بزرگ باینری (BLOB) در نظر گرفته می‌شود (به توصیف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) مراجعه کنید). مقادیر این شمارش مشخص می‌کند که java.io.InputStream چگونه باید هنگام عبور به متد رفتار شود. بر اساس نیازها، تصمیمات مختلفی می‌تواند گرفته شود تا کارایی بهینه‌ترین رفتار ارائه شود.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | جریان تا انتها خوانده می‌شود و سپس آزاد می‌گردد - یعنی |
| [KeepLocked](#KeepLocked) | جریان داخل شیء [IPresentation](../../com.aspose.slides/ipresentation) قفل می‌شود - یعنی |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

جریان تا انتها خوانده می‌شود و سپس آزاد می‌گردد - یعنی تضمین می‌شود که این جریان در آینده توسط نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) استفاده نشود. می‌تواند توسط کد مشتری بسته شود یا به هر روش دیگری به کار رود.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // جریان می‌تواند بسته شود، دیگر برای شیء "pres" نیازی به آن نیست.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

جریان داخل شیء [IPresentation](../../com.aspose.slides/ipresentation) قفل می‌شود - یعنی مالکیت جریان منتقل می‌شود. شیء [IPresentation](../../com.aspose.slides/ipresentation) مسئولیت حذف صحیح جریان را زمانی که این شیء خود پاک شود، بر عهده خواهد داشت. این رفتار زمانی که لازم است یک فایل BLOB بزرگ (مانند ویدیو یا صدا بزرگ - به توصیف [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) مراجعه کنید) را سریال‌سازی کنید و می‌خواهید از بارگذاری این فایل در حافظه یا مشکلات عملکرد دیگر جلوگیری کنید، بسیار مفید است. می‌توانید فقط java.io.FileInputStream را برای این فایل باز کنید و به یک متد پاس دهید و رفتار [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior را انتخاب کنید.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // شما نباید جریان را ببندید یا به آن به روش دیگری تعامل کنید، این منجر به خطا در متد Save خواهد شد.
>    // fileStream برای ذخیره‌سازی استفاده خواهد شد، که از مصرف زیاد حافظه جلوگیری می‌کند
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
