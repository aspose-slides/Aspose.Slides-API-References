---
title: ITextFrame class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/itextframe/
---
## ITextFrame کلاس

Represents a TextFrame.

The ITextFrame type exposes the following members:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/fa/aspose.slides/itextframe/paragraphs/) | فهرست تمام پاراگراف‌ها را در یک فریم برمی‌گرداند.<br/>            فقط-خواندنی [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fa/aspose.slides/itextframe/text/) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند.<br/>            خواندنی/قابل‌نوشتن **str**. |
| [`text_frame_format`](/slides/python-net/fa/aspose.slides/itextframe/text_frame_format/) | شیء قالب‌بندی برای این شیء TextFrame را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextFrameFormat`](/slides/python-net/fa/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/itextframe/hyperlink_queries/) | دسترس آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/fa/aspose.slides/itextframe/parent_shape/) | قاب والد یا None را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکرده باشد<br/>            فقط-خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fa/aspose.slides/itextframe/parent_cell/) | سلول والد یا None را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکرده باشد.<br/>            فقط-خواندنی [`ICell`](/slides/python-net/fa/aspose.slides/icell). |
| [`slide`](/slides/python-net/fa/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/itextframe/presentation/) |  |

## متدها

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`get_text_rect(self)`](/slides/python-net/fa/aspose.slides/itextframe/get_text_rect/#) | مستطیل متن تعریف‌شده توسط هندسهٔ قاب والد را دریافت می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/itextframe/join_portions_with_same_formatting/#) | دنباله‌ها با قالب‌بندی یکسان را در تمام پاراگراف‌ها ترکیب می‌کند. |
| [`split_text_by_columns(self)`](/slides/python-net/fa/aspose.slides/itextframe/split_text_by_columns/#) | محتویات متنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند،  <br/>            که هر عنصر متناظر با یک ستون متن جداگانه در داخل فریم است. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/itextframe/replace_regex/#str-str) | تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند. |


### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)