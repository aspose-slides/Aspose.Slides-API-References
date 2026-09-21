---
title: IRotation3D class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/irotation3d/
---
## IRotation3D 類別

表示圖表的 3D 旋轉。

IRotation3D 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`rotation_x`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/rotation_x/) | 取得或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（範圍為 -90 到 90 度）。<br/>            此屬性對應 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的「Y Rotation」選項。<br/>            讀/寫 **int**. |
| [`rotation_y`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/rotation_y/) | 取得或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（範圍為 0 到 360 度）。<br/>            此屬性對應 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的「X Rotation」選項。<br/>            讀/寫 **int**. |
| [`perspective`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/perspective/) | 取得或設定 3D 圖表的透視值（視野角度）（範圍為 0 到 100）。<br/>            若 RightAngleAxes 屬性值為 true，則忽略此設定。<br/>            讀/寫 **int**. |
| [`right_angle_axes`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/right_angle_axes/) | 決定圖表軸是否呈直角，而非以透視方式繪製。<br/>            換句話說，它決定圖表軸的角度是否獨立於圖表的<br/>            旋轉或仰角。<br/>            讀/寫 **bool**. |
| [`depth_percents`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/depth_percents/) | 取得或設定 3D 圖表的深度，以圖表寬度的百分比表示（範圍為 20% 到 2000%）。<br/>            讀/寫 **int**. |
| [`height_percents`](/slides/python-net/zh-hant/aspose.slides.charts/irotation3d/height_percents/) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（範圍為 5% 到 500%）。<br/>            讀/寫 **int**. |

### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)