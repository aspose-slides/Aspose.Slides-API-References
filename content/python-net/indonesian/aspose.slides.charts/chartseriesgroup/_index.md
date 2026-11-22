---
title: ChartSeriesGroup class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup kelas

Mewakili grup seri.

Tipe ChartSeriesGroup mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/type/) | Mengembalikan tipe dari grup seri ini.<br/>            Hanya-baca [`CombinableSeriesTypesGroup`](/slides/python-net/id/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder.<br/>            Hanya-baca **bool**. |
| [`series`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/series/) | Mengembalikan koleksi seri.<br/>            Hanya-baca [`IChartSeriesReadonlyCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Menyediakan akses ke batang naik/turun pada diagram Garis atau Saham.<br/>            Hanya-baca [`IUpDownBarsManager`](/slides/python-net/id/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/gap_width/) | Mendapatkan atau mengatur ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom.<br/>            Nilai harus antara 0 dan 500.<br/>            Baca/tulis **int**. |
| [`gap_depth`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/gap_depth/) | Mendapatkan atau mengatur jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda.<br/>            Nilai harus antara 0 dan 500.<br/>            Baca/tulis **int**. |
| [`first_slice_angle`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Mendapatkan atau mengatur sudut irisan pertama diagram pai atau donat, <br/>            dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat).<br/>            Baca/tulis **int**. |
| [`doughnut_hole_size`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Menentukan ukuran lubang pada diagram donat (bisa antara 0 dan 90 persen <br/>            dari ukuran area plot).<br/>            Baca/tulis **int**. |
| [`overlap`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/overlap/) | Menentukan seberapa banyak batang dan kolom harus saling tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%).<br/>             - -100%: Jarak maksimum (batang benar-benar terpisah).<br/>             - 0%: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak.<br/>             - 100%: Tumpang tindih maksimum (batang benar-benar tumpang tindih satu sama lain).<br/>             Properti ini adalah baca/tulis **int**. |
| [`second_pie_size`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Menentukan ukuran pai atau batang kedua pada diagram pai-dalam-pai atau <br/>            diagram batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa <br/>            antara 5 dan 200 persen).<br/>            Baca/tulis **int**. |
| [`bubble_size_representation`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada diagram gelembung.<br/>            Baca/tulis [`BubbleSizeRepresentationType`](/slides/python-net/id/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana <br/>            yang berada pada pai atau batang kedua pada diagram pai-dalam-pai atau diagram batang-dalam-pai. <br/>            Digunakan bersama properti PieSplitBy.<br/>            Baca/tulis **float**. |
| [`pie_split_by`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Menentukan cara menentukan titik data mana yang berada pada pai atau batang kedua <br/>            pada diagram pai-dalam-pai atau diagram batang-dalam-pai.<br/>            Baca/tulis [`PieSplitType`](/slides/python-net/id/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda.<br/>            Baca/tulis **bool**. |
| [`has_series_lines`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Benar jika diagram memiliki garis seri. Diterapkan pada diagram batang bertumpuk dan OfPie.<br/>            Baca/tulis **bool**. |
| [`hi_low_lines_format`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Menentukan format HiLowLines. <br/>            HiLowLines diterapkan dengan tipe diagram HiLowClose, OpenHiLowClose, VolumeHiLowClose, dan VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Menentukan faktor skala untuk diagram gelembung (bisa <br/>            antara 0 dan 300 persen dari ukuran default).<br/>            Baca/tulis **int**. |
| [`pie_split_custom_points`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Informasi pemisahan khusus untuk diagram pai-dalam-pai atau batang-dalam-pai dengan pemisahan khusus.<br/>            Berisi titik data yang harus digambar pada pai atau batang kedua dalam diagram pai-dalam-pai atau <br/>            batang-dalam-pai.<br/>            Hanya-baca [`PieSplitCustomPointCollection`](/slides/python-net/id/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/chart/) | Mengembalikan diagram induk.<br/>            Hanya-baca [`IChart`](/slides/python-net/id/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Mendapatkan elemen pada indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup.  
2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup (“series group properties”).  
   “Series group properties” dalam kelas ChartSeriesGroup bersifat baca/tulis.  
   Setiap “series group properties” dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.  


### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)