---
title: Audio class
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/audio/
---
## کلاس Audio

نمایانگر یک فایل صوتی توکار.

نوع Audio اعضای زیر را ارائه می‌دهد:

## خصوصیات

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/fa/aspose.slides/audio/content_type/) | MIME type یک صوت را که در [`Audio.binary_data`](/slides/python-net/fa/aspose.slides/audio/binary_data) رمزگذاری شده است، برمی‌گرداند.<br/>            فقط-خواندنی **str**. |
| [`binary_data`](/slides/python-net/fa/aspose.slides/audio/binary_data/) | کپی داده‌های یک صوت را برمی‌گرداند. در صورت وجود مقدار زیادی داده، <br/>            استفاده از متد [`Audio.get_stream`](/slides/python-net/fa/aspose.slides/audio/get_stream) را در نظر بگیرید تا از بارگذاری غیرضروری  داده‌های صوت<br/>            به حافظه یا حتی استثنای OutOfMemoryException جلوگیری شود.<br/>            فقط-خواندنی **int**[]. |

## متدها

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/fa/aspose.slides/audio/get_stream/#) | یک Stream برای خواندن برمی‌گرداند.<br/>            از 'using' استفاده کنید یا پس از استفاده، جریان را بسته کنید. |


### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)