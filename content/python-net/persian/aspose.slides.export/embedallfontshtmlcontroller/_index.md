---
title: EmbedAllFontsHtmlController class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController کلاس

کلاس کنترل‌کننده فرمت‌بندی برای استفاده در جاسازی همه قلم‌های ارائه در قالب WOFF.

نوع EmbedAllFontsHtmlController اعضای زیر را ارائه می‌دهد:

## سازندگان

| سازنده | توضیح |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | یک نمونه جدید ایجاد می‌کند |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | یک نمونه جدید ایجاد می‌کند |

## متدها

| متد | توضیح |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | برای نوشتن سرصفحه سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود. |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | برای نوشتن پاورقی سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود. |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | برای نوشتن سرصفحه اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود. |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | برای نوشتن پاورقی اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود. |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | قبل از رندر شدن شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، تکهٔ html افزوده‌شده درج می‌شود و تصویر جدید بر روی قبلی آغاز می‌شود. |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | قبل از رندر شدن شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، تکهٔ html افزوده‌شده درج می‌شود و تصویر جدید بر روی قبلی آغاز می‌شود. |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | تمام قلم‌های موجود در [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) را می‌نویسد. |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/fa/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | داده‌ها را به صورت base64 در خود سند HTML می‌نویسد. |


### موارد مرتبط
* ماژول [`aspose.slides.export`](/slides/python-net/fa/aspose.slides.export)
* کتابخانه [`Aspose.Slides`](/slides/python-net)