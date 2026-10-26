---
title: GeometryPath class
second_title: Aspose.Slides for Python 透過 .NET API 參考文件
description:
type: docs
url: /zh-hant/aspose.slides/geometrypath/
---
## GeometryPath 類別

表示 GeometryShape 的幾何路徑

GeometryPath 型別公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/__init__/#) | 建立 GeometryPath 的實例 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`path_data`](/slides/python-net/zh-hant/aspose.slides/geometrypath/path_data/) | 傳回 GeometryShape 的幾何路徑，作為路徑段陣列。 |
| [`fill_mode`](/slides/python-net/zh-hant/aspose.slides/geometrypath/fill_mode/) | 設定填充模式 |
| [`stroke`](/slides/python-net/zh-hant/aspose.slides/geometrypath/stroke/) | 設定筆畫外觀 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#asposeslidespointf) | 在路徑末端加入直線 |
| [`line_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#float-float) | 在路徑末端加入直線 |
| [`line_to(self, point, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | 在路徑指定位置加入直線 |
| [`line_to(self, x, y, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#float-float-int) | 在路徑指定位置加入直線 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | 在路徑末端加入三次 Bezier 曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 在路徑末端加入三次 Bezier 曲線 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | 在路徑指定位置加入三次 Bezier 曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 在路徑指定位置加入三次 Bezier 曲線 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | 在路徑末端加入二次 Bezier 曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | 在路徑末端加入二次 Bezier 曲線 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | 在路徑指定位置加入二次 Bezier 曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | 在路徑指定位置加入二次 Bezier 曲線 |
| [`move_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/move_to/#asposeslidespointf) | 設定下一個點的位置。 |
| [`move_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/move_to/#float-float) | 設定下一個點的位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/remove_at/#int) | 移除幾何路徑中指定索引的段。 |
| [`close_figure(self)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/close_figure/#) | 關閉此路徑的當前圖形 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/arc_to/#float-float-float-float) | 將指定的弧形附加至路徑。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)