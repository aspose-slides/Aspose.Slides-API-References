---
title: IRotation3D class
second_title: Aspose.Slides dla Pythona poprzez .NET Odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/irotation3d/
---
## IRotation3D klasa

Reprezentuje obrót 3D wykresu.

Typ IRotation3D udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`rotation_x`](/slides/python-net/pl/aspose.slides.charts/irotation3d/rotation_x/) | Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees).<br/>            The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+.<br/>            Odczyt/zapis **int**. |
| [`rotation_y`](/slides/python-net/pl/aspose.slides.charts/irotation3d/rotation_y/) | Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees).<br/>            The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+.<br/>            Odczyt/zapis **int**. |
| [`perspective`](/slides/python-net/pl/aspose.slides.charts/irotation3d/perspective/) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100).<br/>            Ignored if RightAngleAxes property value is true.<br/>            Odczyt/zapis **int**. |
| [`right_angle_axes`](/slides/python-net/pl/aspose.slides.charts/irotation3d/right_angle_axes/) | Determines whether the chart axes are at right angles, rather than drawn in perspective.<br/>            In other words it determines whether the chart angles of axes are independent from chart <br/>            rotation or elevation.<br/>            Odczyt/zapis **bool**. |
| [`depth_percents`](/slides/python-net/pl/aspose.slides.charts/irotation3d/depth_percents/) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent).<br/>            Odczyt/zapis **int**. |
| [`height_percents`](/slides/python-net/pl/aspose.slides.charts/irotation3d/height_percents/) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent).<br/>            Odczyt/zapis **int**. |


### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)