---
title: IRotation3D class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IRotation3D class

Represents 3D rotation of a chart.

The IRotation3D type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [rotation_x](/slides/python-net/aspose.slides.charts/rotation_x) | Returns or sets the rotation degree around the X-axis, i.e. in the Y direction for 3D charts (between -90 and 90 degrees).<br/>            The property matches with the 21.2.2.157 rotX (X Rotation) item in ECMA-376 and with the "Y Rotation" option in PowerPoint 2007+.<br/>            Read/write :py:class:`int`. |
| [rotation_y](/slides/python-net/aspose.slides.charts/rotation_y) | Returns or sets the rotation degree around the Y-axis, i.e. in the X direction for 3D charts (between 0 and 360 degrees).<br/>            The property matches with the 21.2.2.158 rotY (Y Rotation) item in ECMA-376 and with the "X Rotation" option in PowerPoint 2007+.<br/>            Read/write :py:class:`int`. |
| [perspective](/slides/python-net/aspose.slides.charts/perspective) | Returns or sets the perspective value (field of view angle) for 3D charts (between 0 and 100).<br/>            Ignored if RightAngleAxes property value is true.<br/>            Read/write :py:class:`int`. |
| [right_angle_axes](/slides/python-net/aspose.slides.charts/right_angle_axes) | Determines whether the chart axes are at right angles, rather than drawn in perspective.<br/>            In other words it determines whether the chart angles of axes are independent from chart <br/>            rotation or elevation.<br/>            Read/write :py:class:`bool`. |
| [depth_percents](/slides/python-net/aspose.slides.charts/depth_percents) | Returns or sets the depth of a 3D chart as a percentage of a chart width (between 20 and 2000 percent).<br/>            Read/write :py:class:`int`. |
| [height_percents](/slides/python-net/aspose.slides.charts/height_percents) | Specifies the height of a 3-D chart as a percentage of the chart width (between 5 and 500 percent).<br/>            Read/write :py:class:`int`. |

