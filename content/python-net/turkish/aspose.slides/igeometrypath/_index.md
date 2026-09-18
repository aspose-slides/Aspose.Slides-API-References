---
title: IGeometryPath class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igeometrypath/
---
## IGeometryPath sınıfı

GeometryShape'in geometri yolunu temsil eder

IGeometryPath türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`path_data`](/slides/python-net/tr/aspose.slides/igeometrypath/path_data/) | GeometryShape'in geometri yolunu yol segmentleri dizisi olarak döndürür. |
| [`fill_mode`](/slides/python-net/tr/aspose.slides/igeometrypath/fill_mode/) | Dolgu kipini ayarlar |
| [`stroke`](/slides/python-net/tr/aspose.slides/igeometrypath/stroke/) | Kontür görünümünü ayarlar |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/tr/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf) | Yolu sonuna çizgi ekler |
| [`line_to(self, x, y)`](/slides/python-net/tr/aspose.slides/igeometrypath/line_to/#float-float) | Yolu sonuna çizgi ekler |
| [`line_to(self, point, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/line_to/#asposepydrawingpointf-int) | Yolun belirtilen yerine çizgi ekler |
| [`line_to(self, x, y, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/line_to/#float-float-int) | Yolun belirtilen yerine çizgi ekler |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/tr/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/tr/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | Yolun belirtilen yerine kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Yolun belirtilen yerine kübik Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/tr/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | Yolun sonuna ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/tr/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float) | Yolun sonuna ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | Yolun belirtilen yerine ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/quadratic_bezier_to/#float-float-float-float-int) | Yolun belirtilen yerine ikinci dereceden Bezier eğrisi ekler |
| [`move_to(self, point)`](/slides/python-net/tr/aspose.slides/igeometrypath/move_to/#asposepydrawingpointf) | Sonraki nokta konumunu ayarlar. |
| [`move_to(self, x, y)`](/slides/python-net/tr/aspose.slides/igeometrypath/move_to/#float-float) | Sonraki nokta konumunu ayarlar. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/igeometrypath/remove_at/#int) | Geometri yolunun belirtilen indeksteki segmenti kaldırır. |
| [`close_figure(self)`](/slides/python-net/tr/aspose.slides/igeometrypath/close_figure/#) | Bu yolun mevcut figürünü kapatır |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/tr/aspose.slides/igeometrypath/arc_to/#float-float-float-float) | Yola belirtilen yayı ekler. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)