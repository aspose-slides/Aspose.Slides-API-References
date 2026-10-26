---
title: GeometryPath class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/geometrypath/
---
## GeometryPath kelas

Mewakili jalur geometri dari GeometryShape

Tipe GeometryPath menampilkan anggota-anggota berikut:

## Konstruktor

| Constructor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides/geometrypath/__init__/#) | Membuat instance dari GeometryPath |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`path_data`](/slides/python-net/id/aspose.slides/geometrypath/path_data/) | Mengembalikan jalur geometri dari GeometryShape sebagai array segmen jalur. |
| [`fill_mode`](/slides/python-net/id/aspose.slides/geometrypath/fill_mode/) | Mengatur mode isi |
| [`stroke`](/slides/python-net/id/aspose.slides/geometrypath/stroke/) | Mengatur tampilan stroke |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/id/aspose.slides/geometrypath/line_to/#asposeslidespointf) | Menambahkan garis ke akhir jalur |
| [`line_to(self, x, y)`](/slides/python-net/id/aspose.slides/geometrypath/line_to/#float-float) | Menambahkan garis ke akhir jalur |
| [`line_to(self, point, index)`](/slides/python-net/id/aspose.slides/geometrypath/line_to/#asposeslidespointf-int) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [`line_to(self, x, y, index)`](/slides/python-net/id/aspose.slides/geometrypath/line_to/#float-float-int) | Menambahkan garis ke tempat yang ditentukan pada jalur |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/id/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf) | Menambahkan kurva Bezier kubik di akhir jalur |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/id/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | Menambahkan kurva Bezier kubik di akhir jalur |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/id/aspose.slides/geometrypath/cubic_bezier_to/#asposeslidespointf-asposeslidespointf-asposeslidespointf-int) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/id/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | Menambahkan kurva Bezier kubik ke tempat yang ditentukan pada jalur |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/id/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/id/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | Menambahkan kurva Bezier kuadratik di akhir jalur |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/id/aspose.slides/geometrypath/quadratic_bezier_to/#asposeslidespointf-asposeslidespointf-int) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/id/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | Menambahkan kurva Bezier kuadratik ke tempat yang ditentukan pada jalur |
| [`move_to(self, point)`](/slides/python-net/id/aspose.slides/geometrypath/move_to/#asposeslidespointf) | Mengatur posisi titik berikutnya. |
| [`move_to(self, x, y)`](/slides/python-net/id/aspose.slides/geometrypath/move_to/#float-float) | Mengatur posisi titik berikutnya. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides/geometrypath/remove_at/#int) | Menghapus segmen pada indeks yang ditentukan dari jalur geometri. |
| [`close_figure(self)`](/slides/python-net/id/aspose.slides/geometrypath/close_figure/#) | Menutup bentuk saat ini dari jalur ini |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/id/aspose.slides/geometrypath/arc_to/#float-float-float-float) | Menambahkan arc yang ditentukan ke jalur. |


### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)