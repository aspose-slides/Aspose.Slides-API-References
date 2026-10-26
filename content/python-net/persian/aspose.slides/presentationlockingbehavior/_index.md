---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior شمارش

رفتار مربوط به نحوهٔ برخورد با منبع [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) (فایل یا **io.RawIOBase**) در حین بارگذاری و کار با یک نمونه از [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) را نشان می‌دهد.

نوع PresentationLockingBehavior اعضای زیر را ارائه می‌دهد:

## فیلدها

| فیلد | توضیح |
| :- | :- |
| LOAD_AND_RELEASE | منبع فقط برای مدت زمان اجرای سازنده [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) قفل می‌شود.<br/> اگر [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) به false تنظیم شود، تمام BLOBها <br/> در حافظه بارگذاری می‌شوند. در غیر این صورت، روش‌های دیگری مانند فایل‌های موقت ممکن است استفاده شوند. این رفتار نسبت به [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/fa/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) کندتر است، و اگر امکان انتقال مالکیت منبع به [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) وجود داشته باشد، استفاده از [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/fa/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) توصیه می‌شود. |
| KEEP_LOCKED | منبع برای کل طول عمر نمونهٔ [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) قفل می‌شود، تا زمانی که آن <br/> از بین برود.<br/> [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) باید برای استفاده از <br/> این رفتار روی true تنظیم شود، در غیر این صورت استثنایی پرتاب خواهد شد. این رفتار توصیه می‌شود، سریع‌تر است و نسبت به [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/fa/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE) حافظه کمتری مصرف می‌کند. |

### ملاحظات

منبع پارامتری است که به سازندهٔ [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) پاس داده می‌شود. در مثال زیر، منبع فایل «pres.pptx» است:

برای این مثال، منبع (فایل «pres.pptx») برای طول عمر یک نمونهٔ [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) قفل می‌شود، یعنی نمی‌توان آن را توسط فرآیند دیگر تغییر یا حذف کرد.

### موارد مرتبط
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)