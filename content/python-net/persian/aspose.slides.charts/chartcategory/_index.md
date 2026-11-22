---
title: ChartCategory class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/chartcategory/
---
## ChartCategory کلاس

دسته‌های نمودار را نمایندگی می‌کند.

نوع ChartCategory اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`use_cell`](/slides/python-net/fa/aspose.slides.charts/chartcategory/use_cell/) | اگر مقدار true باشد، ویژگی AsCell فعال است. به عبارت دیگر، worksheet برای <br/>            ذخیره‌سازی دسته استفاده می‌شود (این حالت از دسته‌بندی چند سطحی پشتیبانی می‌کند).<br/>            اگر مقدار false باشد، ویژگی AsLiteral فعال است. به عبارت دیگر، worksheet برای <br/>            ذخیره‌سازی دسته استفاده نمی‌شود (و این حالت از دسته‌های چند سطحی پشتیبانی نمی‌کند).<br/>            فقط-خواندنی **bool**. |
| [`as_cell`](/slides/python-net/fa/aspose.slides.charts/chartcategory/as_cell/) | مقدار یا تنظیم شیء IChartDataCell.<br/>            اگر دسته چند سطحی باشد، از شیء IChartDataCell برای سطح "0" استفاده می‌شود.<br/>            خواندن/نوشتن [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fa/aspose.slides.charts/chartcategory/as_literal/) | مقدار یا تنظیم شیء AsLiteral.<br/>            خواندن/نوشتن **any**. |
| [`value`](/slides/python-net/fa/aspose.slides.charts/chartcategory/value/) | اگر UseCell مقدار true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است.<br/>            اگر UseCell مقدار false باشد، این ویژگی نمایانگر ویژگی AsLiteral است.<br/>            خواندن/نوشتن **any**. |
| [`grouping_levels`](/slides/python-net/fa/aspose.slides.charts/chartcategory/grouping_levels/) | مخزن مدیریتی مقادیر سطوح گروه‌بندی دسته‌ نمودار.<br/>            دسته‌بندی چندسطحی دارای بیش از یک سطح گروه‌بندی است.<br/>            ایندکس‌بندی سطوح گروه‌بندی از صفر شروع می‌شود.<br/>            فقط-خواندنی [`IChartCategoryLevelsManager`](/slides/python-net/fa/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/fa/aspose.slides.charts/chartcategory/cached_value/) | مقدار کش‌شده یک دسته‌ نمودار را برمی‌گرداند.<br/>            فقط-خواندنی [`ICachedChartValue`](/slides/python-net/fa/aspose.slides.charts/icachedchartvalue). |

## متدها

| متد | توضیح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/chartcategory/remove/#) | دسته را از نمودار حذف می‌کند. |


### موارد مرتبط
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)