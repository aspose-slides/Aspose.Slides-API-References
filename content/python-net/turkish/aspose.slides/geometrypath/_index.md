---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/geometrypath/
---
## GeometryPath sınıfı

GeometryShape'ın geometri yolunu temsil eder

GeometryPath türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides/geometrypath/__init__/#) | GeometryPath örneği oluşturur |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`path_data`](/slides/python-net/tr/aspose.slides/geometrypath/path_data/) | GeometryShape'ın geometri yolunu yol segmentleri dizisi olarak döndürür. |
| [`fill_mode`](/slides/python-net/tr/aspose.slides/geometrypath/fill_mode/) | Dolgu modunu ayarlar |
| [`stroke`](/slides/python-net/tr/aspose.slides/geometrypath/stroke/) | Çizgi görünümünü ayarlar |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Yola sonuna bir çizgi ekler |
| [`line_to(self, x, y)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#float-float) | Yola sonuna bir çizgi ekler |
| [`line_to(self, point, index)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Yolda belirtilen konuma bir çizgi ekler |
| [`line_to(self, x, y, index)`](/slides/python-net/tr/aspose.slides/geometrypath/line_to/#float-float-int) | Yolda belirtilen konuma bir çizgi ekler |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Yolun sonuna kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Yolda belirtilen konuma kübik Bezier eğrisi ekler |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/tr/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Yolda belirtilen konuma kübik Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Yolun sonuna ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Yolun sonuna ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Yolda belirtilen konuma ikinci dereceden Bezier eğrisi ekler |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/tr/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Yolda belirtilen konuma ikinci dereceden Bezier eğrisi ekler |
| [`move_to(self, point)`](/slides/python-net/tr/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Sonraki nokta konumunu ayarlar. |
| [`move_to(self, x, y)`](/slides/python-net/tr/aspose.slides/geometrypath/move_to/#float-float) | Sonraki nokta konumunu ayarlar. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides/geometrypath/remove_at/#int) | Geometri yolunda belirtilen indeksteki segmenti kaldırır. |
| [`close_figure(self)`](/slides/python-net/tr/aspose.slides/geometrypath/close_figure/#) | Bu yolun mevcut şekli kapatır |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/tr/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Yola belirtilen yayı ekler. |

### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)