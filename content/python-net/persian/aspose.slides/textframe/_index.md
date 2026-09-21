---
title: TextFrame class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/textframe/
---
## کلاس TextFrame

نمایانگر یک TextFrame است.

نوع TextFrame اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/fa/aspose.slides/textframe/paragraphs/) | فهرست تمام پاراگراف‌ها در یک فریم را برمی‌گرداند.<br/>            فقط خواندنی [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fa/aspose.slides/textframe/text/) | متن ساده برای یک TextFrame را دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`text_frame_format`](/slides/python-net/fa/aspose.slides/textframe/text_frame_format/) | شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند.<br/>            فقط خواندنی [`ITextFrameFormat`](/slides/python-net/fa/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/textframe/hyperlink_queries/) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/fa/aspose.slides/textframe/slide/) | اسلاید والد TextFrame را برمی‌گرداند.<br/>            فقط خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/textframe/presentation/) | پریزنټیشن والد TextFrame را برمی‌گرداند.<br/>            فقط خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/fa/aspose.slides/textframe/parent_shape/) | شکل والد را برمی‌گرداند یا None اگر شیء والد واسط IShape را پیاده‌سازی نکند<br/>            فقط خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fa/aspose.slides/textframe/parent_cell/) | سلول والد را برمی‌گرداند یا None اگر شیء والد واسط ICell را پیاده‌سازی نکند.<br/>            فقط خواندنی [`ICell`](/slides/python-net/fa/aspose.slides/icell). |

## متدها

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/textframe/join_portions_with_same_formatting/#) | دنباله‌های با قالب‌بندی یکسان را در تمام پاراگراف‌ها به هم می‌پیوندد. |
| [`split_text_by_columns(self)`](/slides/python-net/fa/aspose.slides/textframe/split_text_by_columns/#) | محتوای متنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند،<br/>            که هر عنصر متناظر با یک ستون متنی جداگانه در داخل فریم است. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص شده را با متن دیگر مشخص شده جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/textframe/replace_regex/#str-str) | تمام مطابقت‌های عبارت منظم را با رشته مشخص شده جایگزین می‌کند. |

### ملاحظات دیگر
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)