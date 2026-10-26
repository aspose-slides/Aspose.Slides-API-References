---
title: LoadingStreamBehavior
second_title: مرجع API Aspose.Slides برای جاوا
description: java.io.InputStream که به یک متد پاس داده می‌شود به عنوان یک شیء بزرگ باینری (BLOB) در نظر گرفته می‌شود؛ توضحیات را ببینید.
type: docs
url: /fa/com.aspose.slides/loadingstreambehavior/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream که به یک متد پاس داده می‌شود به عنوان یک شیء بزرگ باینری (BLOB) در نظر گرفته می‌شود (به توضیح [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) مراجعه کنید). مقادیر این enumeration مشخص می‌کنند که java.io.InputStream هنگام پاس شدن به متد چگونه رفتار کند. بسته به نیازها، تصمیمات مختلفی می‌تواند برای ارائه کارآمدترین رفتار اتخاذ شود.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | جریان تا انتها خوانده می‌شود و سپس رها می‌شود - یعنی |
| [KeepLocked](#KeepLocked) | جریان در داخل شیء [IPresentation](../../com.aspose.slides/ipresentation) قفل می‌شود، یعنی |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

جریان تا انتها خوانده می‌شود و سپس رها می‌شود - یعنی تضمین می‌شود که این جریان در آینده توسط نمونه [IPresentation](../../com.aspose.slides/ipresentation) استفاده نخواهد شد. می‌تواند توسط کد مشتری بسته شود یا به هر روش دیگری استفاده شود.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // جریان می‌تواند بسته شود، دیگر برای شیء "pres" مورد نیاز نیست.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

جریان در داخل شیء [IPresentation](../../com.aspose.slides/ipresentation) قفل می‌شود، یعنی مالکیت جریان منتقل می‌شود. شیء [IPresentation](../../com.aspose.slides/ipresentation) مسئول خواهد بود که جریان را به‌درستی هنگام آزادسازی این شیء حذف کند. این رفتار زمانی که نیاز به سریال‌سازی یک فایل BLOB بزرگ (مانند یک ویدیو یا صوت بزرگ - ببینید توضیح [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) داشته باشید و بخواهید بارگذاری این فایل در حافظه یا مشکلات عملکردی دیگر را جلوگیری کنید، بسیار مفید است. می‌توانید فقط java.io.FileInputStream برای این فایل باز کنید و به یک متد پاس کنید، با انتخاب [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // نباید جریان را ببندید یا به روش دیگری با آن تعامل داشته باشید، این منجر به خطا در متد Save می‌شود.
>    // fileStream برای ذخیره استفاده خواهد شد، که از مصرف زیاد حافظه جلوگیری می‌کند
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```