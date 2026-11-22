---
title: IDataLabelCollection class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection کلاس

نمایانگر برچسب‌های یک سری است.

نوع IDataLabelCollection اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| خاصیت | توضیح |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | فرمت پیش‌فرض تمام برچسب‌های داده در مجموعه را بازمی‌گرداند.<br/>            فقط خواندنی [`IDataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | فرمت خطوط راهنمای برچسب‌های داده را نمایان می‌کند.<br/>            فقط خواندنی [`IChartLinesFormat`](/slides/python-net/fa/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/is_visible/) | مقدار False به این معنی است که برچسب داده به‌صورت پیش‌فرض قابل مشاهده نیست (و بنابراین تمام <br/>            پرچم‌های Show* (ShowValue, ...) از ویژگی DefaultDataLabelFormat برابر false هستند).<br/>            فقط خواندنی **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | تعداد برچسب‌های داده قابل مشاهده در مجموعه را دریافت می‌کند.<br/>            فقط خواندنی **int**. |
| [`count`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/count/) | تعداد تمام برچسب‌های داده در مجموعه را دریافت می‌کند.<br/>            فقط خواندنی **int**. |
| [`parent_series`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/parent_series/) | سری نمودار والد را بازمی‌گرداند.<br/>            فقط خواندنی [`IChartSeries`](/slides/python-net/fa/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | نوع شکل پیش‌فرض برای برچسب‌های داده را دریافت یا تنظیم می‌کند.<br/>            اگر شکلی تعریف نشده باشد، [`ShapeType.NOT_DEFINED`](/slides/python-net/fa/aspose.slides/shapetype/NOT_DEFINED) را بازمی‌گرداند. |
| [`chart`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/presentation/) |  |

برچسب داده را برای نقطه داده با ایندکس مشخص دریافت می‌کند.

## ایندکسر

| نام | توضیح |
| :- | :- |
| [`[index]`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## متدها

| متد | توضیح |
| :- | :- |
| [`hide(self)`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/hide/#) | برچسب داده را به‌صورت پیش‌فرض مخفی می‌کند با تنظیم همه پرچم‌های Show* (ShowValue, ...) از ویژگی <br/>            DefaultDataLabelFormat به وضعیت false.<br/>            پس از این، IsVisible برابر false خواهد بود. |
| [`index_of(self, value)`](/slides/python-net/fa/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | یک اندیس از DataLabel مشخص شده در مجموعه را بازمی‌گرداند. |

### مراجع
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)