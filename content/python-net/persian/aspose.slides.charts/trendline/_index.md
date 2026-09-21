---
title: Trendline class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/trendline/
---
## Trendline کلاس

کلاس نمایانگر خط روند سری نمودار است

نوع Trendline اعضای زیر را نمایش می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`trendline_name`](/slides/python-net/fa/aspose.slides.charts/trendline/trendline_name/) | دریافت یا تنظیم نام خط روند.<br/>            فقط‌خواندنی **str**. |
| [`trendline_type`](/slides/python-net/fa/aspose.slides.charts/trendline/trendline_type/) | دریافت یا تنظیم نوع خط روند.<br/>            فقط‌خواندنی [`TrendlineType`](/slides/python-net/fa/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/fa/aspose.slides.charts/trendline/format/) | نمایانگر فرمت خط روند.<br/>            فقط‌خواندنی [`IFormat`](/slides/python-net/fa/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/fa/aspose.slides.charts/trendline/backward/) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پخش) که خط روند قبل از<br/>            داده‌های سری مورد ترند ادامه می‌یابد. در نمودارهای پخش و غیرپخش، مقدار باید هر مقدار غیرمنفی باشد.<br/>            فقط‌خواندنی **float**. |
| [`forward`](/slides/python-net/fa/aspose.slides.charts/trendline/forward/) | تعیین تعداد دسته‌ها (یا واحدها در نمودار پخش) که خط روند پس از داده‌های سری مورد ترند ادامه می‌یابد. در نمودارهای پخش و غیرپخش، مقدار باید هر مقدار غیرمنفی باشد.<br/>            فقط‌خواندنی **float**. |
| [`intercept`](/slides/python-net/fa/aspose.slides.charts/trendline/intercept/) | مقداری را مشخص می‌کند که در آن خط روند محور y را قطع می‌کند. این ویژگی تنها زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد.<br/>            فقط‌خواندنی **float**. |
| [`display_equation`](/slides/python-net/fa/aspose.slides.charts/trendline/display_equation/) | مشخص می‌کند که معادله خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که مقدار Rsquaredvalue قرار دارد).<br/>            فقط‌خواندنی **bool**. |
| [`order`](/slides/python-net/fa/aspose.slides.charts/trendline/order/) | مرتبه خط روند چندجمله‌ای را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد.<br/>            فقط‌خواندنی **int**. |
| [`period`](/slides/python-net/fa/aspose.slides.charts/trendline/period/) | دوره خط روند برای خط روند میانگین متحرک را تعیین می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد.<br/>            فقط‌خواندنی **int**. |
| [`display_r_squared_value`](/slides/python-net/fa/aspose.slides.charts/trendline/display_r_squared_value/) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار نمایش داده شود (در همان برچسبی که معادله قرار دارد).<br/>            فقط‌خواندنی **bool**. |
| [`related_legend_entry`](/slides/python-net/fa/aspose.slides.charts/trendline/related_legend_entry/) | نمایانگر ورودی لگند مرتبط با این خط روند<br/>            فقط‌خواندنی [`ILegendEntryProperties`](/slides/python-net/fa/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/fa/aspose.slides.charts/trendline/text_frame_for_overriding/) | می‌تواند شامل متن قالب‌بندی‌شده غنی باشد. اگر این ویژگی None نباشد، این مقدار متن قالب‌بندی‌شده متن تولید خودکار برچسب داده را بازنویسی می‌کند.<br/>            متن تولید خودکار برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، <br/>            ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود.<br/>            فقط‌خواندنی [`ITextFrame`](/slides/python-net/fa/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/fa/aspose.slides.charts/trendline/text_format/) | فرمت متن را برمی‌گرداند.<br/>            فقط‌خواندنی [`IChartTextFormat`](/slides/python-net/fa/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/trendline/chart/) | نمودار والد را برمی‌گرداند.<br/>            فقط‌خواندنی [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/trendline/presentation/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/fa/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | TextFrameForOverriding را با متنی که در پارامتر "text" آمده است، مقداردهی اولیه کنید.<br/>            اگر TextFrameForOverriding پیش از این مقداردهی شده باشد، به سادگی متن آن را تغییر می‌دهد. |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)