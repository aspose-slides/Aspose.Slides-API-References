---
title: ITextFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/itextframe/
---
## ITextFrame کلاس

یک TextFrame را نمایش می‌دهد.

نوع ITextFrame اعضای زیر را در‌اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`paragraphs`](/slides/python-net/fa/aspose.slides/itextframe/paragraphs/) | فهرست تمام پاراگراف‌ها در یک فریم را برمی‌گرداند.<br/>            فقط-خواندنی [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fa/aspose.slides/itextframe/text/) | متن ساده یک TextFrame را می‌گیرد یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`text_frame_format`](/slides/python-net/fa/aspose.slides/itextframe/text_frame_format/) | شیء قالب‌بندی این شیء TextFrame را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextFrameFormat`](/slides/python-net/fa/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/itextframe/hyperlink_queries/) | دسترسی آسان به پیوندهای درون‌گذشته را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/fa/aspose.slides/itextframe/parent_shape/) | شکل والد را برمی‌گرداند یا None اگر شیء والد رابط IShape را پیاده‌سازی نکند<br/>            فقط-خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fa/aspose.slides/itextframe/parent_cell/) | سلول والد را برمی‌گرداند یا None اگر شیء والد رابط ICell را پیاده‌سازی نکند.<br/>            فقط-خواندنی [`ICell`](/slides/python-net/fa/aspose.slides/icell). |
| [`slide`](/slides/python-net/fa/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides/itextframe/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fa/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/itextframe/join_portions_with_same_formatting/#) | بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌ها به هم می‌پیوندد. |
| [`split_text_by_columns(self)`](/slides/python-net/fa/aspose.slides/itextframe/split_text_by_columns/#) | محتوای متنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe) را به آرایه‌ای از رشته‌ها تقسیم می‌کند،<br/>            که هر عنصر به یک ستون متنی جداگانه در داخل فریم مربوط می‌شود. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/itextframe/replace_regex/#str-str) | تمام مطابقت‌های عبارت منظم را با رشته‌ی مشخص‌شده جایگزین می‌کند. |


### نگاه کنید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)