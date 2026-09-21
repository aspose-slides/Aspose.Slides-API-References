---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/geometrypath/
---
## GeometryPath 類別

表示 GeometryShape 的幾何路徑

GeometryPath 類型公開以下成員：

## 建構函式

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/__init__/#) | 建立 GeometryPath 的實例 |

## 屬性

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/zh-hant/aspose.slides/geometrypath/path_data/) | 返回 GeometryShape 的幾何路徑，作為路徑段的陣列。 |
| [`fill_mode`](/slides/python-net/zh-hant/aspose.slides/geometrypath/fill_mode/) | 設定填充模式 |
| [`stroke`](/slides/python-net/zh-hant/aspose.slides/geometrypath/stroke/) | 設定筆畫外觀 |

## 方法

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | 在路徑末端加入直線 |
| [`line_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#float-float) | 在路徑末端加入直線 |
| [`line_to(self, point, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | 在路徑的指定位置加入直線 |
| [`line_to(self, x, y, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/line_to/#float-float-int) | 在路徑的指定位置加入直線 |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | 在路徑末端加入三次貝塞爾曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 在路徑末端加入三次貝塞爾曲線 |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | 在路徑的指定位置加入三次貝塞爾曲線 |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 在路徑的指定位置加入三次貝塞爾曲線 |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | 在路徑末端加入二次貝塞爾曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | 在路徑末端加入二次貝塞爾曲線 |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | 在路徑的指定位置加入二次貝塞爾曲線 |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | 在路徑的指定位置加入二次貝塞爾曲線 |
| [`move_to(self, point)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | 設定下一個點的位置。 |
| [`move_to(self, x, y)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/move_to/#float-float) | 設定下一個點的位置。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/remove_at/#int) | 移除幾何路徑中指定索引的段 |
| [`close_figure(self)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/close_figure/#) | 關閉此路徑的目前圖形 |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/zh-hant/aspose.slides/geometrypath/arc_to/#float-float-float-float) | 將指定的弧線附加到路徑。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)