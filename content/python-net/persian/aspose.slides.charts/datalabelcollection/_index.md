---
title: DataLabelCollection class
second_title: راهنمای API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection کلاس

نمایانگر برچسب‌های یک سری.

نوع DataLabelCollection اعضای زیر را در دسترس قرار می‌دهد:

## ویژگی‌ها

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/chart/) | چارت والد را برمی‌گرداند.<br/>            فقط قابل خواندن [`IChart`](/slides/python-net/fa/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/is_visible/) | False به این معناست که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و به همین دلیل همه پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat نادرست هستند).<br/>            فقط قابل خواندن **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | تعداد برچسب‌های داده‌ی قابل مشاهده در مجموعه را دریافت می‌کند.<br/>            فقط قابل خواندن **int**. |
| [`count`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/count/) | تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند.<br/>            فقط قابل خواندن **int**. |
| [`default_data_label_format`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/default_data_label_format/) | قالب پیش‌فرض برچسب داده را دریافت می‌کند.<br/>            فقط قابل خواندن [`IDataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/leader_lines_format/) | قالب خطوط راهنمای برچسب‌های داده را نشان می‌دهد.<br/>             فقط قابل خواندن [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/parent_series/) | سری والد را دریافت می‌کند.<br/>            فقط قابل خواندن [`IChartSeries`](/slides/python-net/fa/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/presentation/) |  |

برچسب داده را برای نقطه داده‌ای با ایندکس مشخص شده دریافت می‌کند.

## ایندکسر

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## متدها

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/hide/#) | برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat به حالت نادرست.<br/>            IsVisible پس از این نادرست خواهد بود. |
| [`index_of(self, value)`](/slides/python-net/fa/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | ایندکس برچسب دادهٔ مشخص‌شده در مجموعه را برمی‌گرداند. |

### نگاه کنید به
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)