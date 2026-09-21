---
title: StreamWrapper class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/streamwrapper/
---
## کلاس StreamWrapper

پوشش Aspose.IO.Stream برای رابط COM.

نوع StreamWrapper اعضای زیر را نشان می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`stream`](/slides/python-net/fa/aspose.slides/streamwrapper/stream/) | یک جریان را دریافت می‌کند.<br/>            فقط-خواندنی **io.RawIOBase**. |
| [`can_read`](/slides/python-net/fa/aspose.slides/streamwrapper/can_read/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان جاری از خواندن پشتیبانی می‌کند.<br/>            فقط-خواندنی **bool**. |
| [`can_seek`](/slides/python-net/fa/aspose.slides/streamwrapper/can_seek/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان جاری از جستجو پشتیبانی می‌کند.<br/>            فقط-خواندنی **bool**. |
| [`can_write`](/slides/python-net/fa/aspose.slides/streamwrapper/can_write/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان جاری از نوشتن پشتیبانی می‌کند.<br/>            فقط-خواندنی **bool**. |
| [`length`](/slides/python-net/fa/aspose.slides/streamwrapper/length/) | طول جریان به بایت را برمی‌گرداند.<br/>            فقط-خواندنی **int**. |
| [`position`](/slides/python-net/fa/aspose.slides/streamwrapper/position/) | موقعیت داخل جریان جاری را می‌گیرد یا تنظیم می‌کند.<br/>            فقط-خواندنی **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`close(self)`](/slides/python-net/fa/aspose.slides/streamwrapper/close/#) | جریان جاری را می‌بندد و هر منبعی را آزاد می‌کند. |
| [`flush(self)`](/slides/python-net/fa/aspose.slides/streamwrapper/flush/#) | تمام بافرهای این جریان را پاک می‌کند و باعث می‌شود هر دادهٔ بافرشده‌ای به دستگاه زیرین نوشته شود. |
| [`read(self, buffer, offset, count)`](/slides/python-net/fa/aspose.slides/streamwrapper/read/#bytes-int-int) | یک توالی بایت را از جریان جاری می‌خواند و موقعیت داخل جریان را به میزان بایت‌های خوانده‌شده پیش می‌برد. |
| [`read_byte(self)`](/slides/python-net/fa/aspose.slides/streamwrapper/read_byte/#) | یک بایت را از جریان می‌خواند و موقعیت داخل جریان را یک بایت جلو می‌برد، یا اگر به انتهای جریان رسیده باشد -1 باز می‌گرداند. |
| [`seek(self, offset, origin)`](/slides/python-net/fa/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | موقعیت داخل جریان جاری را تنظیم می‌کند |
| [`write(self, buffer, offset, count)`](/slides/python-net/fa/aspose.slides/streamwrapper/write/#bytes-int-int) | یک توالی بایت را به جریان جاری می‌نویسد و موقعیت جاری داخل این جریان را به میزان بایت‌های نوشته‌شده پیش می‌برد. |
| [`write_byte(self, value)`](/slides/python-net/fa/aspose.slides/streamwrapper/write_byte/#int) | یک بایت را در موقعیت جاری داخل جریان می‌نویسد و موقعیت داخل جریان را یک بایت جلو می‌برد. |

### موارد دیگر
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)