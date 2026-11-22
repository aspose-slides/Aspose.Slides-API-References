---
title: IChartSeriesGroup class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartseriesgroup/
---
## kelas IChartSeriesGroup

Mewakili grup seri.

Tipe IChartSeriesGroup mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`type`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/type/) | Mengembalikan tipe dari grup seri ini.<br/>            Hanya-baca [`CombinableSeriesTypesGroup`](/slides/python-net/id/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Menunjukkan apakah seri grup ini diplot pada sumbu sekunder.<br/>            Hanya-baca **bool**. |
| [`series`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/series/) | Mengembalikan koleksi hanya-baca dari seri diagram.<br/>            Hanya-baca [`IChartSeriesReadonlyCollection`](/slides/python-net/id/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Menyediakan akses ke batang naik/turun pada grafik Garis atau Stok.<br/>            Hanya-baca [`IUpDownBarsManager`](/slides/python-net/id/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/gap_width/) | Mendapatkan atau menetapkan ruang antara klaster batang atau kolom, sebagai persentase lebar batang atau kolom.<br/>            Nilai harus antara 0 dan 500.<br/>            Baca/tulis **int**. |
| [`gap_depth`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Mendapatkan atau menetapkan jarak antara seri data dalam diagram 3D, sebagai persentase lebar penanda.<br/>            Nilai harus antara 0 dan 500.<br/>            Baca/tulis **int**. |
| [`first_slice_angle`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Mendapatkan atau menetapkan sudut irisan pertama diagram pai atau donat, <br/>            dalam derajat (searah jarum jam dari atas, dari 0 hingga 360 derajat).<br/>            Baca/tulis **int**. |
| [`is_color_varied`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Menentukan bahwa setiap penanda data dalam seri memiliki warna yang berbeda.<br/>            Baca/tulis **bool**. |
| [`has_series_lines`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Benar jika bagan memiliki garis seri. Diterapkan pada bagan batang bertumpuk dan OfPie.<br/>            Baca/tulis **bool**. |
| [`overlap`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/overlap/) | Menentukan seberapa banyak batang dan kolom tumpang tindih pada bagan 2-D, sebagai persentase (dari -100 % hingga 100 %).<br/>             - -100 %: Jarak maksimum (batang terpisah sepenuhnya).<br/>             - 0 %: Batang ditempatkan berdampingan tanpa tumpang tindih atau jarak.<br/>             - 100 %: Tumpang tindih maksimum (batang sepenuhnya menutupi satu sama lain).<br/>             Properti ini dapat dibaca/ditulis **int**. |
| [`second_pie_size`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Menentukan ukuran pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai, sebagai persentase ukuran pai pertama (bisa antara 5 hingga 200 %).<br/>            Baca/tulis **int**. |
| [`pie_split_position`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Menentukan nilai yang akan digunakan untuk menentukan titik data mana yang berada di pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai.<br/>            Digunakan bersama properti PieSplitBy.<br/>            Baca/tulis **float**. |
| [`pie_split_by`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Menentukan cara menentukan titik data mana yang berada di pai atau batang kedua pada bagan pai-dalam-pai atau batang-dalam-pai.<br/>            Baca/tulis [`PieSplitType`](/slides/python-net/id/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Informasi pemisahan kustom untuk bagan pai-dalam-pai atau batang-dalam-pai dengan pemisahan kustom.<br/>            Berisi titik data yang akan digambar di pai atau batang kedua dalam bagan pai-dalam-pai atau batang-dalam-pai.<br/>            Hanya-baca [`IPieSplitCustomPointCollection`](/slides/python-net/id/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Menentukan ukuran lubang pada bagan donat (bisa antara 10 hingga 90 % ukuran area plot).<br/>            Baca/tulis **int**. |
| [`bubble_size_scale`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Menentukan faktor skala untuk bagan gelembung (bisa antara 0 hingga 300 % ukuran default).<br/>            Baca/tulis **int**. |
| [`hi_low_lines_format`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Menentukan format HiLowLines. <br/>            HiLowLines diterapkan dengan tipe bagan HiLowClose, OpenHiLowClose, VolumeHiLowClose dan VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Menentukan bagaimana nilai ukuran gelembung direpresentasikan pada bagan gelembung.<br/>            Baca/tulis [`BubbleSizeRepresentationType`](/slides/python-net/id/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Mendapatkan elemen pada indeks yang ditentukan.

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Catatan

1) Lihat ringkasan dan catatan untuk kelas ChartSeriesGroupCollection dan enum CombinableSeriesTypesGroup.  
2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri").  
   "Properti grup seri" dalam kelas ChartSeriesGroup dapat dibaca/ditulis.  
   Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.  

### Lihat Juga
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* perpustakaan [`Aspose.Slides`](/slides/python-net)