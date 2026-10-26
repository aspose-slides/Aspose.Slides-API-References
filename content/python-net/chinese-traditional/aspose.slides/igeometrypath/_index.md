---
title: IGeometryPath class
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/igeometrypath/
---
## IGeometryPath 類別

表示 GeometryShape 的幾何路徑

IGeometryPath 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`path_data`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/path_data/) | 傳回 GeometryShape 的幾何路徑，作為路徑段的陣列。 |
| [`fill_mode`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/fill_mode/) | 設定填充模式 |
| [`stroke`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/stroke/) | 設定筆畫外觀 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/line_to/#asposeslidespointf) | 將直線加入路徑的末端 |
| [`line_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/line_to/#float-float) | 將直線加入路徑的末端 |
| [`line_to(self, point, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/line_to/#asposeslidespointf-int) | 將直線加入路徑的指定位置 |
| [`line_to(self, x, y, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/line_to/#float-float-int) | 將直線加入路徑的指定位置 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | 在路徑的末端加入三次貝茲曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 在路徑的末端加入三次貝茲曲線 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | 在路徑的指定位置加入三次貝茲曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 在路徑的指定位置加入三次貝茲曲線 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | 在路徑的末端加入二次貝茲曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | 在路徑的末端加入二次貝茲曲線 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | 在路徑的指定位置加入二次貝茲曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | 在路徑的指定位置加入二次貝茲曲線 |
| [`move_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/move_to/#asposeslidespointf) | 設定下一個點的位置。 |
| [`move_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/move_to/#float-float) | 設定下一個點的位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/remove_at/#int) | 移除幾何路徑中指定索引的段落。 |
| [`close_figure(self)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/close_figure/#) | 關閉此路徑的目前圖形 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/zh-hant/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | 將指定的弧線附加到路徑。 |

### 參見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)