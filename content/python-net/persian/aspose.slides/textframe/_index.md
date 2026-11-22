---
title: TextFrame class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/textframe/
---
## TextFrame کلاس

نمایانگر یک TextFrame است.

نوع TextFrame اعضای زیر را در اختیار می‌گذارد:

## خصوصیات

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/fa/aspose.slides/textframe/paragraphs/) | لیست تمام پاراگراف‌ها را در یک فریم برمی‌گرداند.<br/>            فقط‌خواندنی [`IParagraphCollection`](/slides/python-net/fa/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/fa/aspose.slides/textframe/text/) | دریافت یا تنظیم متن ساده برای یک TextFrame.<br/>            قابل‌خواندن/قابل‌نوشتن **str**. |
| [`text_frame_format`](/slides/python-net/fa/aspose.slides/textframe/text_frame_format/) | شیء قالب‌بندی را برای این شیء TextFrame برمی‌گرداند.<br/>            فقط‌خواندنی [`ITextFrameFormat`](/slides/python-net/fa/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/fa/aspose.slides/textframe/hyperlink_queries/) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند.<br/>            فقط‌خواندنی [`IHyperlinkQueries`](/slides/python-net/fa/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/fa/aspose.slides/textframe/slide/) | اسلاید والد TextFrame را برمی‌گرداند.<br/>            فقط‌خواندنی [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/fa/aspose.slides/textframe/presentation/) | ارائهٔ نمایش والد TextFrame را برمی‌گرداند.<br/>            فقط‌خواندنی [`IPresentation`](/slides/python-net/fa/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/fa/aspose.slides/textframe/parent_shape/) | شکل والد یا None را برمی‌گرداند اگر شیء والد رابط IShape را پیاده‌سازی نکند<br/>            فقط‌خواندنی [`IShape`](/slides/python-net/fa/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/fa/aspose.slides/textframe/parent_cell/) | سلول والد یا None را برمی‌گرداند اگر شیء والد رابط ICell را پیاده‌سازی نکند.<br/>            فقط‌خواندنی [`ICell`](/slides/python-net/fa/aspose.slides/icell). |

## متدها

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | تمام موارد عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fa/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | تمام موارد عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fa/aspose.slides/textframe/join_portions_with_same_formatting/#) | اجراهای هم‌فرمت را در تمام پاراگراف‌ها به هم می‌پیوندد. |
| [`split_text_by_columns(self)`](/slides/python-net/fa/aspose.slides/textframe/split_text_by_columns/#) | محتوای متنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe) را به یک آرایه از رشته‌ها تقسیم می‌کند،  <br/>            که هر عنصر متناظر با یک ستون متن جداگانه در داخل فریم است. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fa/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | تمام وقوع‌های متن مشخص‌شده را با متن دیگری که مشخص شده جایگزین می‌کند. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fa/aspose.slides/textframe/replace_regex/#str-str) | تمام موارد عبارت منظم را با رشته مشخص‌شده جایگزین می‌کند. |
| [`get_text_rect(self)`](/slides/python-net/fa/aspose.slides/textframe/get_text_rect/#) | مستطیل متن تعریف‌شده توسط هندسهٔ شکل والد را برمی‌گرداند. |

### موارد مرتبط
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)