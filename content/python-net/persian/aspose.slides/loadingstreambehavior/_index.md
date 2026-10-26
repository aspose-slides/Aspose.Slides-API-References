---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior شمارشی

شی **io.RawIOBase** که به یک متد پاس داده می‌شود به عنوان یک شی باینری بزرگ (BLOB) (به توضیح [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions) مراجعه کنید). مقادیر این شمارشی مشخص می‌کند که **io.RawIOBase** چگونه باید هنگام پاس شدن به متد رفتار کند. بسته به نیازها، تصمیمات متفاوتی می‌تواند گرفته شود تا کارآمدترین رفتار فراهم شود.

نوع LoadingStreamBehavior اعضای زیر را ارائه می‌دهد:

## فیلدها

| فیلد | توضیح |
| :- | :- |
| READ_STREAM_AND_RELEASE | جریان تا انتها خوانده می‌شود و سپس آزاد می‌شود - یعنی تضمین می‌شود که این جریان <br/>            در آینده توسط نمونه [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) استفاده نشود. می‌تواند توسط کد مشتری <br/>            بسته شود یا به هر روش دیگری استفاده شود. |
| KEEP_LOCKED | جریان داخل شی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) قفل می‌شود، یعنی مالکیت <br/>            جریان منتقل می‌شود. شی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation) مسئول خواهد بود که <br/>            به‌درستی جریان را زمانی که این شی خودش تخریب می‌شود، آزاد کند. <br/>            این رفتار زمانی که نیاز به سریالی‌سازی یک فایل BLOB بزرگ دارید (مانند یک <br/>            ویدیو یا صدا بزرگ - به توضیح [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions) مراجعه کنید) و می‌خواهید از بارگذاری <br/>            این فایل به حافظه یا مشکلات عملکردی دیگر جلوگیری کنید، بسیار مفید است. می‌توانید به سادگی **System.IO.FileStream** <br/>            این فایل را باز کرده و به یک متد پاس کنید، با انتخاب [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/fa/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### موارد مرتبط
* کلاس [`IBlobManagementOptions`](/slides/python-net/fa/aspose.slides/iblobmanagementoptions)
* کلاس [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)