---
title: IChartCategory class
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartcategory/
---
## کلاس IChartCategory

دسته‌بندی‌های نمودار را نشان می‌دهد.

نوع IChartCategory اعضای زیر را در دسترس می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`use_cell`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/use_cell/) | اگر مقدار true باشد، ویژگی AsCell فعال است. به عبارت دیگر، worksheet برای <br/> ذخیره‌سازی دسته‌بندی استفاده می‌شود (این حالت از دسته‌بندی چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، ویژگی AsLiteral فعال است. به عبارت دیگر، worksheet برای <br/> ذخیره‌سازی دسته‌بندی استفاده نمی‌شود (و این حالت از دسته‌بندی‌های چندسطحی پشتیبانی نمی‌کند). فقط-خواندنی **bool**. |
| [`as_cell`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/as_cell/) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند.<br/> اگر دسته‌بندی چندسطحی باشد، سپس از شیء IChartDataCell برای سطح "0" استفاده می‌شود.<br/> قابل‌خواندن/نوشتن [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/as_literal/) | اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند.<br/> قابل‌خواندن/نوشتن **any**. |
| [`value`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/value/) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است.<br/> اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است.<br/> قابل‌خواندن/نوشتن **any**. |
| [`cached_value`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/cached_value/) | مقدار کش‌شده‌ی یک دسته‌بندی نمودار را دریافت می‌کند.<br/> فقط-خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/grouping_levels/) | محفظه مدیریت‌شده‌ای برای مقادیر سطوح گروه‌بندی دسته‌بندی نمودار.<br/> دسته‌بندی چندسطحی حاوی بیش از یک سطح گروه‌بندی است.<br/> ایندکس‌گذاری سطوح گروه‌بندی از صفر شروع می‌شود.<br/> فقط-خواندنی [`IChartCategoryLevelsManager`](/slides/python-net/fa/aspose.slides.charts/ichartcategorylevelsmanager). |

## متدها

| متد | توضیح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/remove/#) | دسته‌بندی را از نمودار حذف می‌کند. |

### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)