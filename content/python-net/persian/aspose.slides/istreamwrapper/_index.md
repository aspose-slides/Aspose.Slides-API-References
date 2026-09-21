---
title: IStreamWrapper class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/istreamwrapper/
---
## IStreamWrapper کلاس

Aspose.IO.Stream wrapper for COM interface.

The IStreamWrapper type exposes the following members:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`stream`](/slides/python-net/fa/aspose.slides/istreamwrapper/stream/) | یک جریان را دریافت می‌کند.<br/>            فقط‌خواندنی **io.RawIOBase**. |
| [`can_read`](/slides/python-net/fa/aspose.slides/istreamwrapper/can_read/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان فعلی از خواندن پشتیبانی می‌کند.<br/>            فقط‌خواندنی **bool**. |
| [`can_seek`](/slides/python-net/fa/aspose.slides/istreamwrapper/can_seek/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان فعلی از حرکت (seeking) پشتیبانی می‌کند.<br/>            فقط‌خواندنی **bool**. |
| [`can_write`](/slides/python-net/fa/aspose.slides/istreamwrapper/can_write/) | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا جریان فعلی از نوشتن پشتیبانی می‌کند.<br/>            فقط‌خواندنی **bool**. |
| [`length`](/slides/python-net/fa/aspose.slides/istreamwrapper/length/) | طول جریان بر حسب بایت را دریافت می‌کند.<br/>            فقط‌خواندنی **int**. |
| [`position`](/slides/python-net/fa/aspose.slides/istreamwrapper/position/) | موقعیت داخل جریان فعلی را دریافت می‌کند.<br/>            فقط‌خواندنی **int**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`close(self)`](/slides/python-net/fa/aspose.slides/istreamwrapper/close/#) | جریان فعلی را می‌بندد و هر منبعی را آزاد می‌کند. |
| [`flush(self)`](/slides/python-net/fa/aspose.slides/istreamwrapper/flush/#) | تمام بافرهای این جریان را پاک می‌کند و باعث می‌شود داده‌های بافر شده به دستگاه زیرین نوشته شوند. |
| [`read(self, buffer, offset, count)`](/slides/python-net/fa/aspose.slides/istreamwrapper/read/#bytes-int-int) | دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند و موقعیت داخل جریان را به میزان بایت‌های خوانده‌شده پیش می‌برد. |
| [`read_byte(self)`](/slides/python-net/fa/aspose.slides/istreamwrapper/read_byte/#) | یک بایت را از جریان می‌خواند و موقعیت داخل جریان را یک بایت پیش می‌برد، یا اگر به انتهای جریان رسیده باشد -1 برمی‌گرداند. |
| [`seek(self, offset, origin)`](/slides/python-net/fa/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | موقعیت داخل جریان فعلی را تنظیم می‌کند |
| [`write(self, buffer, offset, count)`](/slides/python-net/fa/aspose.slides/istreamwrapper/write/#bytes-int-int) | دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد و موقعیت جاری داخل این جریان را به میزان بایت‌های نوشته‌شده پیش می‌برد. |
| [`write_byte(self, value)`](/slides/python-net/fa/aspose.slides/istreamwrapper/write_byte/#int) | یک بایت را به موقعیت فعلی در جریان می‌نویسد و موقعیت داخل جریان را یک بایت پیش می‌برد. |

### موارد مرتبط
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)