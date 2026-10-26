---
title: IChartCategory class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/ichartcategory/
---
## IChartCategory کلاس

دسته‌های نمودار را نشان می‌دهد.

نوع IChartCategory اعضای زیر را ارائه می‌دهد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`use_cell`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/use_cell/) | اگر مقدار true باشد، ویژگی AsCell فعّال است. به عبارت دیگر، برگه کاری برای <br/>            ذخیره‌سازی دسته استفاده می‌شود (در این حالت از دسته چند سطحی پشتیبانی می‌شود).<br/>            اگر مقدار false باشد، ویژگی AsLiteral فعّال است. به عبارت دیگر، برگه کاری برای <br/>            ذخیره‌سازی دسته استفاده نمی‌شود (و در این حالت از دسته چند سطحی پشتیبانی نمی‌شود).<br/>            فقط-خواندنی **bool**. |
| [`as_cell`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/as_cell/) | شیء IChartDataCell را برمی‌گرداند یا تنظیم می‌کند.<br/>            اگر دسته چند-سطحی باشد، شیء IChartDataCell برای سطح "0" استفاده می‌شود.<br/>            خواندنی/نوشتنی [`IChartDataCell`](/slides/python-net/fa/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/as_literal/) | اگر UseCell برابر false باشد، AsLiteral را برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **any**. |
| [`value`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/value/) | اگر UseCell برابر true باشد، این ویژگی نمایانگر ویژگی AsCell.Value است.<br/>            اگر UseCell برابر false باشد، این ویژگی نمایانگر ویژگی AsLiteral است.<br/>            خواندنی/نوشتنی **any**. |
| [`grouping_levels`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/grouping_levels/) | محفظهٔ مدیریت‌شدهٔ مقادیر سطوح گروه‌بندی دستهٔ نمودار.<br/>            دستهٔ چند-سطحی شامل بیش از یک سطح گروه‌بندی است.<br/>            ایندکس‌گذاری سطوح گروه‌بندی به صورت صفر-پایه است.<br/>            فقط-خواندنی [`IChartCategoryLevelsManager`](/slides/python-net/fa/aspose.slides.charts/ichartcategorylevelsmanager). |

## متدها

| متد | توضیح |
| :- | :- |
| [`remove(self)`](/slides/python-net/fa/aspose.slides.charts/ichartcategory/remove/#) | دسته را از نمودار حذف می‌کند. |


### همچنین ببینید
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)