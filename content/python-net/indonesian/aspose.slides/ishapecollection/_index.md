---
title: IShapeCollection class
second_title: Referensi API Aspose.Slides untuk Python melalui .NET
description: 
type: docs
url: /id/aspose.slides/ishapecollection/
---
## IShapeCollection kelas

Mewakili koleksi bentuk.

Tipe IShapeCollection mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`parent_group`](/slides/python-net/id/aspose.slides/ishapecollection/parent_group/) | Mendapatkan objek grup bentuk induk untuk koleksi bentuk.<br/>            Baca-saja [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |

Mendapatkan elemen pada indeks yang ditentukan.
            Baca-saja [`IShape`](/slides/python-net/id/aspose.slides/ishape).

## Pengindeks

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides/ishapecollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/id/aspose.slides/ishapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/id/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/id/aspose.slides/ishapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/id/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/id/aspose.slides/ishapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Membuat bingkai Zoom baru dengan gambar yang telah ditentukan sebelumnya dan menambahkannya ke akhir koleksi bentuk.<br/>            pada indeks yang ditentukan. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/id/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Membuat bingkai Section Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/id/aspose.slides/ishapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan sebelumnya dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Membuat bingkai Section Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Membuat bingkai Section Zoom baru dengan gambar yang telah ditentukan sebelumnya dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-str) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/id/aspose.slides/ishapecollection/add_video_frame/#float-float-float-float-ivideo) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/id/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Membuat bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir koleksi bentuk. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/id/aspose.slides/ishapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi bentuk menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/id/aspose.slides/ishapecollection/to_array/#) | Membuat dan mengembalikan array yang berisi semua bentuk. |
| [`to_array(self, start_index, count)`](/slides/python-net/id/aspose.slides/ishapecollection/to_array/#int-int) | Membuat dan mengembalikan array yang berisi semua bentuk dalam rentang yang ditentukan. |
| [`reorder(self, index, shape)`](/slides/python-net/id/aspose.slides/ishapecollection/reorder/#int-ishape) | Memindahkan bentuk yang ditentukan ke posisi baru dalam koleksi bentuk. |
| [`reorder(self, index, shapes)`](/slides/python-net/id/aspose.slides/ishapecollection/reorder/#int-listishape) | Memindahkan bentuk-bentuk yang ditentukan dalam koleksi bentuk, menempatkannya mulai dari indeks yang diberikan. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi bentuk. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/ishapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Membuat auto shape baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menginisialisasinya dengan format template default. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan format template default. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menginisialisasinya dengan styling template default. |
| [`add_group_shape(self)`](/slides/python-net/id/aspose.slides/ishapecollection/add_group_shape/#) | Membuat grup bentuk kosong baru dan menambahkannya ke akhir koleksi bentuk.<br/>            Bingkai grup secara otomatis akan menyesuaikan untuk menampung semua bentuk yang ditambahkan. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_group_shape/#isvgimage-float-float-float-float) | Membuat grup bentuk baru, mengonversi gambar SVG yang ditentukan menjadi bentuk-bentuk individual, dan menambahkan grup yang dihasilkan ke akhir koleksi bentuk. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float) | Membuat bentuk konektor baru dengan styling template default dan menambahkannya ke akhir koleksi bentuk. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/ishapecollection/add_connector/#shapetype-float-float-float-float-bool) | Membuat bentuk konektor baru dan menambahkannya ke akhir koleksi bentuk, secara opsional menerapkan styling template default. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float) | Membuat bentuk konektor baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan styling template default. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Membuat bentuk konektor baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, secara opsional menerapkan styling template default. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_clone/#ishape-float-float-float-float) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/id/aspose.slides/ishapecollection/add_clone/#ishape-float-float) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk baru mempertahankan lebar dan tinggi dari `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/id/aspose.slides/ishapecollection/add_clone/#ishape) | Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk yang dikloning mempertahankan posisi dan ukuran asli. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float-float-float) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_clone/#int-ishape-float-float) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk baru mempertahankan lebar dan tinggi dari `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_clone/#int-ishape) | Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk yang dikloning mempertahankan posisi dan ukuran asli. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/id/aspose.slides/ishapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_summary_zoom_frame/#float-float-float-float) | Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_video_frame/#int-float-float-float-float-str) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_audio_frame_cd/#float-float-float-float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/ishapecollection/add_audio_frame_linked/#float-float-float-float-str) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`index_of(self, shape)`](/slides/python-net/id/aspose.slides/ishapecollection/index_of/#ishape) | Mengembalikan indeks berbasis nol dari kemunculan pertama bentuk yang ditentukan dalam koleksi. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/ishapecollection/add_math_shape/#float-float-float-float) | Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_group_shape(self, index)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_group_shape/#int) | Membuat grup bentuk kosong baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bingkai grup secara otomatis akan menyesuaikan untuk menampung semua bentuk yang ditambahkan. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/id/aspose.slides/ishapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/id/aspose.slides/ishapecollection/add_table/#float-float-listfloat-listfloat) | Membuat tabel baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/id/aspose.slides/ishapecollection/insert_table/#int-float-float-listfloat-listfloat) | Membuat tabel baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides/ishapecollection/remove_at/#int) | Menghapus bentuk pada indeks yang ditentukan dari koleksi bentuk. |
| [`remove(self, shape)`](/slides/python-net/id/aspose.slides/ishapecollection/remove/#ishape) | Menghapus kemunculan pertama bentuk yang ditentukan dari koleksi bentuk. |
| [`clear(self)`](/slides/python-net/id/aspose.slides/ishapecollection/clear/#) | Menghapus semua bentuk dari koleksi bentuk. |


### Lihat Juga
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)