---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometrypath/
---
## GeometryPath sınıfı

GeometryShape nesnesinin geometri yolunu temsil eder

GeometryPath türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/geometrypath/__init__/#) | GeometryPath örneği oluşturur |

## Özellikler

| Property | Description |
| :- | :- |
| [`path_data`](/slides/python-net/tr/aspose.slides/geometrypath/path_data/) | GeometryShape nesnesinin geometri yolunu yol segmentlerinin bir dizisi olarak döndürür. |
| [`fill_mode`](/slides/python-net/tr/aspose.slides/geometrypath/fill_mode/) | Doldurma modunu ayarlar |
| [`stroke`](/slides/python-net/tr/aspose.slides/geometrypath/stroke/) | Çizgi görünümünü ayarlar |

## Metotlar

| Method | Description |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | Yolun sonuna bir çizgi ekler |
| [`line_to(self, x, y)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#float-float) | Yolun sonuna bir çizgi ekler |
| [`line_to(self, point, index)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | Yolun belirtilen konumuna bir çizgi ekler |
| [`line_to(self, x, y, index)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#float-float-int) | Yolun belirtilen konumuna bir çizgi ekler |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Yolun belirtilen konumuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Yolun belirtilen konumuna kübik Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Yolun sonuna ikinci dereceli Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Yolun sonuna ikinci dereceli Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Yolun belirtilen konumuna ikinci dereceli Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Yolun belirtilen konumuna ikinci dereceli Bezier eğrisi ekler |
| [`move_to(self, point)`](/slides/python-net/tr/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | Sonraki nokta konumunu ayarlar |
| [`move_to(self, x, y)`](/slides/python-net/tr/aspose.slides/geometrypath/move_to/#float-float) | Sonraki nokta konumunu ayarlar |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/geometrypath/remove_at/#int) | Geometri yolunun belirtilen indeksindeki segmenti kaldırır |
| [`close_figure(self)`](/slides/python-net/tr/aspose.slides/geometrypath/close_figure/#) | Bu yolun mevcut figürünü kapatır |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/tr/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Yola belirtilen yay ekler |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)