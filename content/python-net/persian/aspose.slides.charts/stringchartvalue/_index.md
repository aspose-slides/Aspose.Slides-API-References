---
title: StringChartValue class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/stringchartvalue/
---
## StringChartValue کلاس

مقدار رشته‌ای را که می‌تواند به دو شکل در سند ارائهٔ pptx ذخیره شود، نمایان می‌کند:
            1) در سلول/سلول‌های کاربرگ مرتبط با نمودار;
            2) به عنوان مقدار لغت‌ساختی.

**Inheritance:**[`StringChartValue`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/fa/aspose.slides.charts/basechartvalue)

نوع StringChartValue اعضای زیر را در اختیار می‌گذارد:

## ویژگی‌ها

| ویژگی | توضیح |
| :- | :- |
| [`data_source_type`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/data_source_type/) | مشخص می‌کند که آیا ویژگی AsCell، AsCells، AsLiteralString یا AsLiteralDouble <br/>            در کلاس‌های مشتق فعال است یا نه. به عبارتی دیگر نوع مقدار ویژگی Data را مشخص می‌کند.<br/>            خواندنی/نوشتنی [`DataSourceType`](/slides/python-net/fa/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/data/) | مقدار یا تنظیم شیء Data.<br/>            خواندنی/نوشتنی **هر**. |
| [`as_cells`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/as_cells/) | اختصاص مقدار Null مجاز نیست.<br/>            مقدار بازگشتی همیشه None نیست.<br/>            خواندنی/نوشتنی [`IChartCellCollection`](/slides/python-net/fa/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/as_literal_string/) | مقدار را به صورت رشتهٔ لغت‌ساختی برمی‌گرداند یا تنظیم می‌کند.<br/>            خواندنی/نوشتنی **str**. |

## متدها

| متد | توضیح |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | مقدار را از سلول مشخص‌شده تنظیم می‌کند. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | اگر ویژگی DataSourceType برابر DataSourceType.Worksheet باشد، این متد آدرس سلول‌های کاربرگی که دادهٔ رشته‌ای را نشان می‌دهند برمی‌گرداند.<br/>            در غیر این صورت، رشتهٔ خالی را برمی‌گرداند. |


### موارد مرتبط
* کلاس [`BaseChartValue`](/slides/python-net/fa/aspose.slides.charts/basechartvalue)
* کلاس [`StringChartValue`](/slides/python-net/fa/aspose.slides.charts/stringchartvalue)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)