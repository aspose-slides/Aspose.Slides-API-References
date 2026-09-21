---
title: StringChartValue class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET การอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.charts/stringchartvalue/
---
## StringChartValue คลาส

Represent string value which can be stored in pptx presentation document in two ways:
            1) ในเซล/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ;
            2) เป็นค่าลิเทอรัล.

**Inheritance:**[`StringChartValue`](/slides/python-net/th/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/th/aspose.slides.charts/basechartvalue)

The StringChartValue type exposes the following members:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`data_source_type`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/data_source_type/) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble <br/>            property is actual in descendants. In other words it specifies the type <br/>            of value of the Data property.<br/>            Read/write [`DataSourceType`](/slides/python-net/th/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/data/) | Returns or sets Data object.<br/>            Read/write **any**. |
| [`as_cells`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/as_cells/) | Null value assigning is not allowed.<br/>            Returning value always is not None.<br/>            Read/write [`IChartCellCollection`](/slides/python-net/th/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/as_literal_string/) | Returns or sets value as literal string.<br/>            Read/write **str**. |

## เมธอด

| Method | Description |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Sets value from specified cell. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/th/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | If DataSourceType property is DataSourceType.Worksheet then this method returns address<br/>            of the cells in workbook which represent the string data. Otherwise return<br/>            empty string. |

### ดูเพิ่มเติม
* class [`BaseChartValue`](/slides/python-net/th/aspose.slides.charts/basechartvalue)
* class [`StringChartValue`](/slides/python-net/th/aspose.slides.charts/stringchartvalue)
* module [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)