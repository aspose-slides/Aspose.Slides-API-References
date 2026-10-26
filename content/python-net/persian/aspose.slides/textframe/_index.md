---
title: TextFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/textframe/
---
## کلاس TextFrame

نشان‌دهنده یک TextFrame است.

نوع TextFrame اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`paragraphs`](/slides/python-net/fa/aspose.slides/textframe/paragraphs/) | فهرست تمام پاراگراف‌ها را در یک فریم برمی‌گرداند.<br/>            فقط-خواندنی [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fa/aspose.slides/textframe/text/) | متن ساده یک TextFrame را دریافت یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |
| [`text_frame_format`](/slides/python-net/fa/aspose.slides/textframe/text_frame_format/) | شیء قالب‌بندی این شیء TextFrame را برمی‌گرداند.<br/>            فقط-خواندنی [`ITextFrameFormat`](/slides/python-net/fa/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/textframe/hyperlink_queries/) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط-خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/fa/aspose.slides/textframe/slide/) | اسلاید والد یک TextFrame را برمی‌گرداند.<br/>            فقط-خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/textframe/presentation/) | ارائهٔ والد یک TextFrame را برمی‌گرداند.<br/>            فقط-خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/fa/aspose.slides/textframe/parent_shape/) | شکل والد را برمی‌گرداند یا None اگر شیء والد رابط IShape را پیاده‌سازی نکرده باشد<br/>            فقط-خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fa/aspose.slides/textframe/parent_cell/) | سلول والد را برمی‌گرداند یا None اگر شیء والد رابط ICell را پیاده‌سازی نکرده باشد.<br/>            فقط-خواندنی [`ICell`](/slides/python-net/fa/aspose.slides/icell). |

## متدها

| متد | توضیح |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | تمام موارد متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | تمام موارد متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | تمام موارد متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | تمام تطابق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | تمام تطابق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/textframe/join_portions_with_same_formatting/#) | بخش‌هایی با قالب‌بندی یکسان در تمام پاراگراف‌ها را به هم می‌پیوندد. |
| [`split_text_by_columns(self)`](/slides/python-net/fa/aspose.slides/textframe/split_text_by_columns/#) | محتویات متنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe) را به یک آرایه از رشته‌ها تقسیم می‌کند،  <br/>            که هر عنصر متناظر با یک ستون متنی جداگانه درون فریم است. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام موارد متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/textframe/replace_regex/#str-str) | تمام تطابق‌های عبارت منظم را با رشته‌ی مشخص‌شده جایگزین می‌کند. |

### مراجع
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)