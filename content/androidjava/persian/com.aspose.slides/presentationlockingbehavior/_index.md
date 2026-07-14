---
title: PresentationLockingBehavior
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: رفتار مربوط به نحوهٔ برخورد با فایل منبع یا java.io.InputStream هنگام بارگذاری و کار با یک نمونهٔ
type: docs
url: /fa/com.aspose.slides/presentationlockingbehavior/
---
**ارث‌بری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

رفتار مربوط به نحوهٔ برخورد با منبع [IPresentation](../../com.aspose.slides/ipresentation) (فایل یا java.io.InputStream) در هنگام بارگذاری و کار با یک نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) را توصیف می‌کند.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

منبع پارامتری است که به سازندهٔ [IPresentation](../../com.aspose.slides/ipresentation) پاس داده می‌شود. در مثال زیر، منبع فایل «pres.pptx» است: برای این مثال، منبع (فایل «pres.pptx») برای طول عمر یک نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، به این معنی که توسط فرآیند دیگر قابل تغییر یا حذف نیست.
## فیلدها

| فیلد | توضیح |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | منبع فقط برای مدت زمان اجرای سازندهٔ [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد. |
| [KeepLocked](#KeepLocked) | منبع برای تمام طول عمر نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، تا زمانی که آن تخریب شود. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

منبع فقط برای مدت زمان اجرای سازندهٔ [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد.

--------------------

اگر ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) بر روی false تنظیم شود، تمام BLOBها در حافظه بارگذاری می‌شوند. در غیر این صورت، ممکن است از روش‌های دیگر مانند فایل‌های موقتی استفاده شود.

--------------------

این رفتار نسبت به [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) کندتر است و اگر امکان انتقال مالکیت منبع به [IPresentation](../../com.aspose.slides/ipresentation) موجود باشد، استفاده از [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) توصیه می‌شود.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

منبع برای تمام طول عمر نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) قفل خواهد شد، تا زمانی که آن تخریب شود.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) باید برای استفاده از این رفتار بر روی true تنظیم شود، در غیر این صورت استثنا پرتاب خواهد شد.

--------------------

این رفتار توصیه می‌شود، سریع‌تر است و نسبت به [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) حافظه کمتری مصرف می‌کند.