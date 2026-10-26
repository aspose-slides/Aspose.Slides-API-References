---
title: PresentationLockingBehavior
second_title: مرجع API Aspose.Slides برای Java
description: رفتار مربوط به برخورد با فایل منبع یا java.io.InputStream هنگام بارگذاری و کار با یک نمونه از آن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/presentationlockingbehavior/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

رفتاری را که در مورد برخورد با منبع [IPresentation](../../com.aspose.slides/ipresentation) (فایل یا java.io.InputStream) هنگام بارگذاری و کار با یک نمونه از [IPresentation](../../com.aspose.slides/ipresentation) تعریف می‌کند، نشان می‌دهد.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

منبع، پارامتر پاس شده به سازنده [IPresentation](../../com.aspose.slides/ipresentation) است. در مثال زیر، منبع فایل "pres.pptx" است: برای این مثال، منبع (فایل "pres.pptx") برای مدت زمان زندگی یک نمونه [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، یعنی توسط پردازش دیگر نمی‌توان آن را تغییر یا حذف کرد.

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | منبع فقط برای مدت زمان اجرای سازنده [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد. |
| [KeepLocked](#KeepLocked) | منبع برای تمام مدت زمان زندگی نمونه [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، تا زمانی که آن دفع شود. |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

منبع فقط برای مدت زمان اجرای سازنده [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد.

--------------------

اگر ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) روی false تنظیم شود، تمام BLOBها در حافظه بارگذاری می‌شوند. در غیر این صورت، روش‌های دیگری مانند فایل‌های موقت ممکن است استفاده شوند.

--------------------

این رفتار نسبت به [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) کندتر است و اگر امکان انتقال مالکیت منبع به [IPresentation](../../com.aspose.slides/ipresentation) وجود داشته باشد، استفاده از [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) توصیه می‌شود.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

منبع برای تمام مدت زمان زندگی نمونه [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، تا زمانی که آن دفع شود.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) باید برای استفاده از این رفتار روی true تنظیم شود، در غیر این صورت استثنا رخ خواهد داد.

--------------------

این رفتار توصیه می‌شود، سریع‌تر است و نسبت به [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) حافظه کمتری مصرف می‌کند.