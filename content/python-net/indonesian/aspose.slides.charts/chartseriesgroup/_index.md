---
title: ChartSeriesGroup class
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup kelas

Mewakili grup seri.

Tipe ChartSeriesGroup menampilkan anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/type/) | Mengembalikan tipe dari grup seri ini.<br/>            Baca-saja [`CombinableSeriesTypesGroup`](/slides/python-net/id/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Menunjukkan apakah seri grup ini dipetakan pada sumbu sekunder.<br/>            Baca-saja **bool**. |
| [`series`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/series/) | Mengembalikan koleksi seri.<br/>            Baca-saja [`IChartSeriesReadonlyCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Menyediakan akses ke batang naik/turun pada diagram Garis atau Stok.<br/>            Baca-saja [`IUpDownBarsManager`](/slides/python-net/id/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/gap_width/) | Menentukan ruang antara kumpulan batang atau kolom, sebagai persentase lebar batang atau kolom.<br/>            Baca/tulis **int**. |
| [`gap_depth`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/gap_depth/) | Mengembalikan atau mengatur jarak, sebagai persentase lebar penanda, antara seri data dalam diagram 3D.<br/>            Baca/tulis **int**. |
| [`first_slice_angle`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Mengatur atau mengubah sudut irisan pertama diagram pai atau donat,<br/>            dalam derajat (searah jarum jam dari atas, dari 0 sampai 360 derajat).<br/>            Baca/tulis **int**. |
| [`doughnut_hole_size`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Menentukan ukuran lubang pada diagram donat (dapat antara 0 dan 90 persen<br/>            dari ukuran area plot).<br/>            Baca/tulis **int**. |
| [`overlap`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/overlap/) | Menentukan berapa banyak batang dan kolom yang saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% sampai 100%).<br/>             - -100%: Jarak maksimum (batang terpisah sepenuhnya).<br/>             - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak.<br/>             - 100%: Tumpang tindih maksimum (batang sepenuhnya menumpuk satu sama lain).<br/>             Properti ini adalah baca/tulis **int**. |
| [`second_pie_size`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau<br/>            batang-dalam-pai, sebagai persentase ukuran pai pertama (dapat<br/>            antara 5 dan 200 persen).<br/>            Baca/tulis **int**. |
| [`bubble_size_representation`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung.<br/>            Baca/tulis [`BubbleSizeRepresentationType`](/slides/python-net/id/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana<br/>            yang berada di pai atau batang kedua pada diagram pai-dalam-pai atau batang-dalam-pai.<br/>            Digunakan bersama properti PieSplitBy.<br/>            Baca/tulis **float**. |
| [`pie_split_by`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua<br/>            pada diagram pai-dalam-pai atau batang-dalam-pai.<br/>            Baca/tulis [`PieSplitType`](/slides/python-net/id/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Menentukan bahwa setiap penanda data dalam seri memiliki warna berbeda.<br/>            Baca/tulis **bool**. |
| [`has_series_lines`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/has_series_lines/) | True jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie.<br/>            Baca/tulis **bool**. |
| [`hi_low_lines_format`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Menentukan format HiLowLines.<br/>            HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Menentukan faktor skala untuk diagram gelembung (dapat antara 0 dan 300 persen ukuran default).<br/>            Baca/tulis **int**. |
| [`pie_split_custom_points`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus.<br/>            Berisi titik data yang harus digambar di pai atau batang kedua dalam diagram pai-dalam-pai atau<br/>            batang-dalam-pai.<br/>            Baca-saja [`PieSplitCustomPointCollection`](/slides/python-net/id/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/chart/) | Mengembalikan diagram induk.<br/>            Baca-saja [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Mendapatkan elemen pada indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup.  
2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri").  
"Properti grup seri" dalam kelas ChartSeriesGroup adalah baca/tulis.  
Setiap "properti grup seri" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.  

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)