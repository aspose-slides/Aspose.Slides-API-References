---
title: Point class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.animation/point/
---
## Kelas Point

Mewakili titik animasi.

Tipe Point menampilkan anggota berikut:

## Konstruktor

| Constructor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.animation/point/__init__/#) | Konstruktor default. |
| [`__init__(self, time, value, formula)`](/slides/python-net/id/aspose.slides.animation/point/__init__/#float-any-str) | Buat titik animasi dengan waktu, nilai, dan formula. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`time`](/slides/python-net/id/aspose.slides.animation/point/time/) | Mewakili nilai waktu.<br/>            Baca/tulis **float**. |
| [`value`](/slides/python-net/id/aspose.slides.animation/point/value/) | Mewakili nilai titik.<br/>            Hanya: bool, ColorFormat, float, int, string.<br/>            Baca/tulis **any**. |
| [`formula`](/slides/python-net/id/aspose.slides.animation/point/formula/) | Formula dalam nilai, atribut from, to, by dapat terdiri dari hal-hal berikut:<br/>            Operator aritmetika standar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Konstanta: ‘pi’ ‘e’<br/>            Operator kondisional: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Operator perbandingan: '==', '>=', '', '!=', '!'<br/>            Operator trigonometri: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritma natural ‘ln()’<br/>            Referensi properti (properti yang didukung host)<br/>            <br/>            contoh: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Baca/tulis **str**. |

### Lihat Juga
* modul [`aspose.slides.animation`](/slides/python-net/id/aspose.slides.animation)
* perpustakaan [`Aspose.Slides`](/slides/python-net)