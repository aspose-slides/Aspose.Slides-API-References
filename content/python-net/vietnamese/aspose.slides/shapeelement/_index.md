---
title: ShapeElement class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/shapeelement/
---
## ShapeElement lớp

Represents a part of shape with same outline and fill properties.

The ShapeElement type exposes the following members:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`parent_shape`](/slides/python-net/vi/aspose.slides/shapeelement/parent_shape/) | Returns a Shape_PPT for which element was created.<br/>            Chỉ-đọc [`Shape`](/slides/python-net/vi/aspose.slides/shape). |
| [`path_points`](/slides/python-net/vi/aspose.slides/shapeelement/path_points/) | Lấy một mảng các điểm xác định hình học của đường dẫn của phần tử. |
| [`path_types`](/slides/python-net/vi/aspose.slides/shapeelement/path_types/) | Gets an array of byte values that specify the type of each point in the element's path. <br/>            <br/>**0**  Cho biết điểm là điểm bắt đầu của một hình.<br/><br/><br/>**1**  Cho biết điểm là một trong hai điểm cuối của một đường thẳng.<br/><br/><br/>**3**  Cho biết điểm là điểm cuối hoặc điểm điều khiển của một spline Bezier bậc ba.<br/><br/><br/>**7**  Che các bit ngoại trừ ba bit thấp, chúng chỉ ra loại điểm.<br/><br/><br/>**16**  Xác định rằng đoạn tương ứng là nét đứt.<br/><br/><br/>**32**  Xác định rằng điểm là một dấu.<br/><br/><br/>**128**  Xác định rằng điểm là điểm cuối cùng trong một đường phụ đóng (hình).<br/><br/><br/>**129**  Cho biết một điểm dữ liệu vừa là đầu cuối của đoạn đường thẳng vừa là điểm cuối cùng của một đường phụ đóng. |
| [`fill_source`](/slides/python-net/vi/aspose.slides/shapeelement/fill_source/) | Trả về thông tin về cách tô màu cho một phần tử.<br/>            Chỉ-đọc [`ShapeElementFillSource`](/slides/python-net/vi/aspose.slides/shapeelementfillsource). |
| [`stroke_source`](/slides/python-net/vi/aspose.slides/shapeelement/stroke_source/) | Trả về thông tin về cách vẽ đường viền cho một phần tử.<br/>            Chỉ-đọc [`ShapeElementStrokeSource`](/slides/python-net/vi/aspose.slides/shapeelementstrokesource). |


### Xem Thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)