---
title: IRotation3D class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/irotation3d/
---
## IRotation3D classe

Rappresenta la rotazione 3D di un grafico.

Il tipo IRotation3D espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`rotation_x`](/slides/python-net/it/aspose.slides.charts/irotation3d/rotation_x/) | Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees).<br/> La proprietà corrisponde all'elemento 21.2.2.157 rotX (X Rotation) in ECMA-376 e all'opzione "Y Rotation" in PowerPoint 2007+.<br/> Read/write **int**. |
| [`rotation_y`](/slides/python-net/it/aspose.slides.charts/irotation3d/rotation_y/) | Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees).<br/> La proprietà corrisponde all'elemento 21.2.2.158 rotY (Y Rotation) in ECMA-376 e all'opzione "X Rotation" in PowerPoint 2007+.<br/> Read/write **int**. |
| [`perspective`](/slides/python-net/it/aspose.slides.charts/irotation3d/perspective/) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100).<br/> Ignored if RightAngleAxes property value is true.<br/> Read/write **int**. |
| [`right_angle_axes`](/slides/python-net/it/aspose.slides.charts/irotation3d/right_angle_axes/) | Determines whether the chart axes are at right angles, rather than drawn in perspective.<br/> In other words it determines whether the chart angles of axes are independent from chart rotation or elevation.<br/> Read/write **bool**. |
| [`depth_percents`](/slides/python-net/it/aspose.slides.charts/irotation3d/depth_percents/) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent).<br/> Read/write **int**. |
| [`height_percents`](/slides/python-net/it/aspose.slides.charts/irotation3d/height_percents/) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent).<br/> Read/write **int**. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)