---
title: ShapeCollection class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/shapecollection/
---
## ShapeCollection kelas

Mewakili kumpulan bentuk.

Tipe ShapeCollection mengekspos anggota-anggota berikut:

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`parent_group`](/slides/python-net/id/aspose.slides/shapecollection/parent_group/) | Mendapatkan objek grup bentuk induk untuk koleksi bentuk.<br/>            Hanya baca [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape). |

Mendapatkan elemen pada indeks yang ditentukan.
            Hanya baca [`IShape`](/slides/python-net/id/aspose.slides/ishape).

## Indexer

| Nama | Deskripsi |
| :- | :- |
| [`[index]`](/slides/python-net/id/aspose.slides/shapecollection/__getitem__/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`add_chart(self, type, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya<br/>            ke akhir koleksi bentuk. |
| [`add_chart(self, type, x, y, width, height, init_with_sample)`](/slides/python-net/id/aspose.slides/shapecollection/add_chart/#asposeslideschartscharttype-float-float-float-float-bool) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan, dan menambahkannya<br/>            ke akhir koleksi bentuk. |
| [`insert_chart(self, type, x, y, width, height, index)`](/slides/python-net/id/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan,<br/>            dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_chart(self, type, x, y, width, height, index, init_with_sample)`](/slides/python-net/id/aspose.slides/shapecollection/insert_chart/#asposeslideschartscharttype-float-float-float-float-int-bool) | Membuat bagan baru, menginisialisasinya dengan data seri contoh dan pengaturan,<br/>            dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_zoom_frame(self, x, y, width, height, slide)`](/slides/python-net/id/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_zoom_frame(self, x, y, width, height, slide, image)`](/slides/python-net/id/aspose.slides/shapecollection/add_zoom_frame/#float-float-float-float-islide-ippimage) | Membuat bingkai Zoom baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide)`](/slides/python-net/id/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide) | Membuat bingkai Zoom baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_zoom_frame(self, index, x, y, width, height, slide, image)`](/slides/python-net/id/aspose.slides/shapecollection/insert_zoom_frame/#int-float-float-float-float-islide-ippimage) | Membuat bingkai Zoom baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk<br/>            pada indeks yang ditentukan. |
| [`add_section_zoom_frame(self, x, y, width, height, section)`](/slides/python-net/id/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection) | Membuat bingkai Zoom Seksi baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_section_zoom_frame(self, x, y, width, height, section, image)`](/slides/python-net/id/aspose.slides/shapecollection/add_section_zoom_frame/#float-float-float-float-isection-ippimage) | Membuat bingkai Zoom Seksi baru dengan gambar yang telah ditentukan dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section)`](/slides/python-net/id/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection) | Membuat bingkai Zoom Seksi baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_section_zoom_frame(self, index, x, y, width, height, section, image)`](/slides/python-net/id/aspose.slides/shapecollection/insert_section_zoom_frame/#int-float-float-float-float-isection-ippimage) | Membuat bingkai Zoom Seksi baru dengan gambar yang telah ditentukan dan menyisipkannya ke dalam koleksi bentuk<br/>            pada indeks yang ditentukan. |
| [`add_ole_object_frame(self, x, y, width, height, data_info)`](/slides/python-net/id/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-ioleembeddeddatainfo) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_ole_object_frame(self, x, y, width, height, class_name, path)`](/slides/python-net/id/aspose.slides/shapecollection/add_ole_object_frame/#float-float-float-float-str-str) | Membuat bingkai objek OLE baru dan menambahkannya ke akhir koleksi bentuk. |
| [`insert_ole_object_frame(self, index, x, y, width, height, data_info)`](/slides/python-net/id/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-ioleembeddeddatainfo) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`insert_ole_object_frame(self, index, x, y, width, height, class_name, path)`](/slides/python-net/id/aspose.slides/shapecollection/insert_ole_object_frame/#int-float-float-float-float-str-str) | Membuat bingkai objek OLE baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. |
| [`add_video_frame(self, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-str) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_video_frame(self, x, y, width, height, video)`](/slides/python-net/id/aspose.slides/shapecollection/add_video_frame/#float-float-float-float-ivideo) | Membuat bingkai video baru dan menambahkannya ke akhir koleksi bentuk. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio_stream)`](/slides/python-net/id/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iorawiobase) | Membuat bingkai audio baru dengan file WAV tersemat dan menambahkannya ke akhir<br/>            koleksi bentuk. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios. |
| [`add_audio_frame_embedded(self, x, y, width, height, audio)`](/slides/python-net/id/aspose.slides/shapecollection/add_audio_frame_embedded/#float-float-float-float-iaudio) | Membuat bingkai audio baru dan menambahkannya ke akhir koleksi bentuk menggunakan<br/>            objek audio yang ada dari daftar Presentation.Audios. |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream)`](/slides/python-net/id/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iorawiobase) | Membuat bingkai audio baru dengan file WAV tersemat dan menyisipkannya ke dalam bentuk<br/>            koleksi pada indeks yang ditentukan. Audio yang tersemat ditambahkan ke koleksi Presentation.Audios<br/>            . |
| [`insert_audio_frame_embedded(self, index, x, y, width, height, audio)`](/slides/python-net/id/aspose.slides/shapecollection/insert_audio_frame_embedded/#int-float-float-float-float-iaudio) | Membuat bingkai audio baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan<br/>            menggunakan objek audio yang ada dari daftar Presentation.Audios. |
| [`to_array(self)`](/slides/python-net/id/aspose.slides/shapecollection/to_array/#) | Membuat dan mengembalikan array yang berisi semua bentuk. |
| [`to_array(self, start_index, count)`](/slides/python-net/id/aspose.slides/shapecollection/to_array/#int-int) | Membuat dan mengembalikan array yang berisi semua bentuk dalam rentang yang ditentukan. |
| [`reorder(self, index, shape)`](/slides/python-net/id/aspose.slides/shapecollection/reorder/#int-ishape) | Memindahkan bentuk yang ditentukan ke posisi baru dalam koleksi bentuk. |
| [`reorder(self, index, shapes)`](/slides/python-net/id/aspose.slides/shapecollection/reorder/#int-listishape) | Memindahkan bentuk-bentuk yang ditentukan dalam koleksi bentuk, menempatkannya mulai dari indeks yang diberikan. |
| [`add_auto_shape(self, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float) | Membuat auto shape baru dengan format default dan menambahkannya ke akhir<br/>            koleksi bentuk. |
| [`add_auto_shape(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/shapecollection/add_auto_shape/#shapetype-float-float-float-float-bool) | Membuat auto shape baru dan menambahkannya ke akhir koleksi bentuk, secara opsional<br/>            menginisialisasinya dengan format template default. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan,<br/>            menerapkan format template default. |
| [`insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/shapecollection/insert_auto_shape/#int-shapetype-float-float-float-float-bool) | Membuat auto shape baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan,<br/>            secara opsional menginisialisasinya dengan gaya template default. |
| [`add_group_shape(self)`](/slides/python-net/id/aspose.slides/shapecollection/add_group_shape/#) | Membuat grup shape kosong baru dan menambahkannya ke akhir koleksi bentuk.<br/>            Frame grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan. |
| [`add_group_shape(self, svg_image, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_group_shape/#isvgimage-float-float-float-float) | Membuat grup shape baru, mengubah gambar SVG yang ditentukan menjadi shape individual,<br/>            dan menambahkan grup yang dihasilkan ke akhir koleksi bentuk. |
| [`add_connector(self, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float) | Membuat shape penghubung baru dengan gaya template default dan menambahkannya ke akhir<br/>            koleksi bentuk. |
| [`add_connector(self, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/shapecollection/add_connector/#shapetype-float-float-float-float-bool) | Membuat shape penghubung baru dan menambahkannya ke akhir koleksi shape,<br/>            secara opsional menerapkan gaya template default. |
| [`insert_connector(self, index, shape_type, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float) | Membuat shape penghubung baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan,<br/>            menerapkan gaya template default. |
| [`insert_connector(self, index, shape_type, x, y, width, height, create_from_template)`](/slides/python-net/id/aspose.slides/shapecollection/insert_connector/#int-shapetype-float-float-float-float-bool) | Membuat shape penghubung baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan,<br/>            secara opsional menerapkan gaya template default. |
| [`add_clone(self, source_shape, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_clone/#ishape-float-float-float-float) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape. |
| [`add_clone(self, source_shape, x, y)`](/slides/python-net/id/aspose.slides/shapecollection/add_clone/#ishape-float-float) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape.<br/>            Shape baru mempertahankan lebar dan tinggi dari `source_shape`. |
| [`add_clone(self, source_shape)`](/slides/python-net/id/aspose.slides/shapecollection/add_clone/#ishape) | Membuat salinan shape yang ditentukan dan menambahkannya ke akhir koleksi shape.<br/>            Shape yang dikloning mempertahankan posisi dan ukuran asli. |
| [`insert_clone(self, index, source_shape, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float-float-float) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [`insert_clone(self, index, source_shape, x, y)`](/slides/python-net/id/aspose.slides/shapecollection/insert_clone/#int-ishape-float-float) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.<br/>            Shape baru mempertahankan lebar dan tinggi dari `source_shape`. |
| [`insert_clone(self, index, source_shape)`](/slides/python-net/id/aspose.slides/shapecollection/insert_clone/#int-ishape) | Membuat salinan shape yang ditentukan dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.<br/>            Shape yang dikloning mempertahankan posisi dan ukuran asli. |
| [`add_smart_art(self, x, y, width, height, layout_type)`](/slides/python-net/id/aspose.slides/shapecollection/add_smart_art/#float-float-float-float-asposeslidessmartartsmartartlayouttype) | Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape. |
| [`add_summary_zoom_frame(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_summary_zoom_frame/#float-float-float-float) | Membuat bingkai Summary Zoom baru dan menambahkannya ke akhir koleksi shape. |
| [`insert_summary_zoom_frame(self, index, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/insert_summary_zoom_frame/#int-float-float-float-float) | Membuat bingkai Summary Zoom baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [`insert_video_frame(self, index, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/shapecollection/insert_video_frame/#int-float-float-float-float-str) | Membuat bingkai video baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [`add_audio_frame_cd(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_audio_frame_cd/#float-float-float-float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menambahkannya ke akhir koleksi shape. |
| [`insert_audio_frame_cd(self, index, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/insert_audio_frame_cd/#int-float-float-float-float) | Membuat bingkai audio baru yang terhubung ke trek CD dan menyisipkannya ke dalam koleksi shape<br/>            pada indeks yang ditentukan. |
| [`add_audio_frame_linked(self, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/shapecollection/add_audio_frame_linked/#float-float-float-float-str) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menambahkannya ke akhir<br/>            koleksi shape. |
| [`insert_audio_frame_linked(self, index, x, y, width, height, fname)`](/slides/python-net/id/aspose.slides/shapecollection/insert_audio_frame_linked/#int-float-float-float-float-str) | Membuat bingkai audio baru yang terhubung ke file audio eksternal dan menyisipkannya ke dalam koleksi shape<br/>            pada indeks yang ditentukan. |
| [`index_of(self, shape)`](/slides/python-net/id/aspose.slides/shapecollection/index_of/#ishape) | Mengembalikan indeks berbasis nol dari kemunculan pertama shape yang ditentukan dalam koleksi. |
| [`add_math_shape(self, x, y, width, height)`](/slides/python-net/id/aspose.slides/shapecollection/add_math_shape/#float-float-float-float) | Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir<br/>            koleksi shape. |
| [`insert_group_shape(self, index)`](/slides/python-net/id/aspose.slides/shapecollection/insert_group_shape/#int) | Membuat grup shape kosong baru dan menyisipkannya ke koleksi shape pada indeks yang ditentukan.<br/>            Frame grup akan otomatis menyesuaikan untuk menampung semua shape yang ditambahkan. |
| [`add_picture_frame(self, shape_type, x, y, width, height, image)`](/slides/python-net/id/aspose.slides/shapecollection/add_picture_frame/#shapetype-float-float-float-float-ippimage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menambahkannya ke akhir<br/>            koleksi shape. |
| [`insert_picture_frame(self, index, shape_type, x, y, width, height, image)`](/slides/python-net/id/aspose.slides/shapecollection/insert_picture_frame/#int-shapetype-float-float-float-float-ippimage) | Membuat bingkai gambar baru yang berisi gambar yang ditentukan dan menyisipkannya ke dalam shape<br/>            koleksi pada indeks yang ditentukan. |
| [`add_table(self, x, y, column_widths, row_heights)`](/slides/python-net/id/aspose.slides/shapecollection/add_table/#float-float-listfloat-listfloat) | Membuat tabel baru dan menambahkannya ke akhir koleksi shape. |
| [`insert_table(self, index, x, y, column_widths, row_heights)`](/slides/python-net/id/aspose.slides/shapecollection/insert_table/#int-float-float-listfloat-listfloat) | Membuat tabel baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan. |
| [`remove_at(self, index)`](/slides/python-net/id/aspose.slides/shapecollection/remove_at/#int) | Menghapus shape pada indeks yang ditentukan dari koleksi shape. |
| [`remove(self, shape)`](/slides/python-net/id/aspose.slides/shapecollection/remove/#ishape) | Menghapus kemunculan pertama shape yang ditentukan dari koleksi shape. |
| [`clear(self)`](/slides/python-net/id/aspose.slides/shapecollection/clear/#) | Menghapus semua shape dari koleksi shape. |


### Lihat Juga
* kelas [`IShape`](/slides/python-net/id/aspose.slides/ishape)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)