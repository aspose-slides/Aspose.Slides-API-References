---
title: StringChartValue class
second_title: مرجع API Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.charts/stringchartvalue/
---
## StringChartValue فئة

يمثل قيمة نصية يمكن تخزينها في مستند عرض pptx بطريقتين:
1) في خلية/خلويات من المصنف المرتبط بالمخطط;
2) كقيمة حرفية.

**الوراثة:**[`StringChartValue`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/ar/aspose.slides.charts/basechartvalue)

نوع StringChartValue يعرض الأعضاء التالية:

## الخصائص

| الخاصية | الوصف |
| :- | :- |
| [`data_source_type`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/data_source_type/) | يحدد ما إذا كانت الخاصية AsCell, AsCells, AsLiteralString أو AsLiteralDouble <br/>            فعلية في الفروع. بمعنى آخر يحدد نوع <br/>            قيمة الخاصية Data.<br/>            قراءة/كتابة [`DataSourceType`](/slides/python-net/ar/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/data/) | إرجاع أو تعيين كائن Data.<br/>            قراءة/كتابة **any**. |
| [`as_cells`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/as_cells/) | إسناد قيمة Null غير مسموح.<br/>            إرجاع القيمة دائماً ليس None.<br/>            قراءة/كتابة [`IChartCellCollection`](/slides/python-net/ar/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/as_literal_string/) | إرجاع أو تعيين القيمة كسلسلة حرفية.<br/>            قراءة/كتابة **str**. |

## الطرق

| الطريقة | الوصف |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | يضبط القيمة من الخلية المحددة. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | إذا كانت الخاصية DataSourceType هي DataSourceType.Worksheet فإن هذه الطريقة تُرجع عنوان الخلايا في المصنف الذي يمثل بيانات السلسلة. وإلا تُرجع سلسلة فارغة. |

### انظر أيضًا
* فئة [`BaseChartValue`](/slides/python-net/ar/aspose.slides.charts/basechartvalue)
* فئة [`StringChartValue`](/slides/python-net/ar/aspose.slides.charts/stringchartvalue)
* وحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* مكتبة [`Aspose.Slides`](/slides/python-net)