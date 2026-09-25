---
title: Presentation class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/presentation/
---
## Kelas Presentation

Mewakili presentasi Microsoft PowerPoint.

Tipe Presentation menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides/presentation/__init__/#) | Konstruktor ini membuat presentasi baru dari awal.<br/>            Presentasi yang dibuat memiliki satu slide kosong. |
| [`__init__(self, load_options)`](/slides/python-net/id/aspose.slides/presentation/__init__/#loadoptions) | Konstruktor ini membuat presentasi baru dari awal.<br/>            Presentasi yang dibuat memiliki satu slide kosong. |
| [`__init__(self, stream)`](/slides/python-net/id/aspose.slides/presentation/__init__/#iorawiobase) | Konstruktor ini adalah mekanisme utama untuk membaca Presentation yang ada. |
| [`__init__(self, stream, load_options)`](/slides/python-net/id/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Konstruktor ini adalah mekanisme utama untuk membaca Presentation yang ada. |
| [`__init__(self, file)`](/slides/python-net/id/aspose.slides/presentation/__init__/#str) | Konstruktor ini mendapatkan jalur file sumber dari mana<br/>             konten Presentation dibaca. |
| [`__init__(self, file, load_options)`](/slides/python-net/id/aspose.slides/presentation/__init__/#str-loadoptions) | Konstruktor ini mendapatkan jalur file sumber dari mana<br/>            konten Presentation dibaca. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`current_date_time`](/slides/python-net/id/aspose.slides/presentation/current_date_time/) | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime.<br/>            Waktu pembuatan objek Presentation ini secara default.<br/>            Baca/tulis **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/id/aspose.slides/presentation/header_footer_manager/) | Mengembalikan manajer HeaderFooter yang aktual.<br/>            Baca saja [`IPresentationHeaderFooterManager`](/slides/python-net/id/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/id/aspose.slides/presentation/protection_manager/) | Mendapatkan manajer izin untuk presentasi ini.<br/>            Baca saja [`IProtectionManager`](/slides/python-net/id/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/id/aspose.slides/presentation/slides/) | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi.<br/id/>            Baca saja [`ISlideCollection`](/slides/python-net/id/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/id/aspose.slides/presentation/sections/) | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi.<br/>            Baca saja [`ISectionCollection`](/slides/python-net/id/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/id/aspose.slides/presentation/slide_size/) | Mengembalikan objek ukuran slide.<br/>            Baca saja [`ISlideSize`](/slides/python-net/id/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/id/aspose.slides/presentation/notes_size/) | Mengembalikan objek ukuran slide catatan.<br/>            Baca saja [`INotesSize`](/slides/python-net/id/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/id/aspose.slides/presentation/layout_slides/) | Mengembalikan daftar semua slide tata letak yang didefinisikan dalam presentasi.<br/>            Baca saja [`IGlobalLayoutSlideCollection`](/slides/python-net/id/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/id/aspose.slides/presentation/masters/) | Mengembalikan daftar semua master slide yang didefinisikan dalam presentasi.<br/>            Baca saja [`IMasterSlideCollection`](/slides/python-net/id/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/id/aspose.slides/presentation/master_notes_slide_manager/) | Mengembalikan manajer master catatan.<br/>            Baca saja [`IMasterNotesSlideManager`](/slides/python-net/id/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/id/aspose.slides/presentation/master_handout_slide_manager/) | Mengembalikan manajer master handout.<br/>            Baca saja [`IMasterHandoutSlideManager`](/slides/python-net/id/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/id/aspose.slides/presentation/fonts_manager/) | Mengembalikan manajer font.<br/>            Baca saja [`IFontsManager`](/slides/python-net/id/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/id/aspose.slides/presentation/default_text_style/) | Mengembalikan gaya teks default untuk shape.<br/>            Baca saja [`ITextStyle`](/slides/python-net/id/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/id/aspose.slides/presentation/comment_authors/) | Mengembalikan koleksi penulis komentar.<br/>            Baca saja [`ICommentAuthorCollection`](/slides/python-net/id/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/id/aspose.slides/presentation/document_properties/) | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan kustom.<br/>            Baca saja [`IDocumentProperties`](/slides/python-net/id/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/id/aspose.slides/presentation/images/) | Mengembalikan koleksi semua gambar dalam presentasi.<br/>            Baca saja [`IImageCollection`](/slides/python-net/id/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/id/aspose.slides/presentation/audios/) | Mengembalikan koleksi semua file audio tersemat dalam presentasi.<br/>            Baca saja [`IAudioCollection`](/slides/python-net/id/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/id/aspose.slides/presentation/videos/) | Mengembalikan koleksi semua file video tersemat dalam presentasi.<br/>            Baca saja [`IVideoCollection`](/slides/python-net/id/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/id/aspose.slides/presentation/slide_show_settings/) | Mengembalikan pengaturan pertunjukan slide untuk presentasi. |
| [`digital_signatures`](/slides/python-net/id/aspose.slides/presentation/digital_signatures/) | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi.<br/>            Baca saja [`IDigitalSignatureCollection`](/slides/python-net/id/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/id/aspose.slides/presentation/custom_data/) | Mengembalikan data kustom presentasi.<br/>            Baca saja [`ICustomData`](/slides/python-net/id/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/id/aspose.slides/presentation/all_custom_xml_parts/) | Mengembalikan semua bagian data kustom dalam presentasi.<br/>            Baca saja [`ICustomXmlPart`](/slides/python-net/id/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/id/aspose.slides/presentation/vba_project/) | Mendapatkan atau mengatur proyek VBA dengan makro presentasi.<br/>            Baca/tulis [`IVbaProject`](/slides/python-net/id/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/id/aspose.slides/presentation/hyperlink_queries/) | Menyediakan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan).<br/>            Baca saja [`IHyperlinkQueries`](/slides/python-net/id/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/id/aspose.slides/presentation/view_properties/) | Mendapatkan properti tampilan seluruh presentasi.<br/>            Baca saja [`IViewProperties`](/slides/python-net/id/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/id/aspose.slides/presentation/first_slide_number/) | Mewakili nomor slide pertama dalam presentasi |
| [`sensitivity_labels`](/slides/python-net/id/aspose.slides/presentation/sensitivity_labels/) | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi.<br/>            Baca saja [`ISensitivityLabelCollection`](/slides/python-net/id/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/id/aspose.slides/presentation/source_format/) | Mengembalikan informasi tentang format dari mana presentasi dimuat.<br/>            Baca saja [`SourceFormat`](/slides/python-net/id/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/id/aspose.slides/presentation/master_theme/) | Mengembalikan tema master.<br/>            Baca saja [`IMasterTheme`](/slides/python-net/id/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/id/aspose.slides/presentation/presentation/) |  |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/id/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Menyimpan semua slide presentasi ke sebuah file dengan format yang ditentukan. |
| [`save(self, stream, format)`](/slides/python-net/id/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Menyimpan semua slide presentasi ke sebuah stream dalam format yang ditentukan. |
| [`save(self, fname, format, options)`](/slides/python-net/id/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/id/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Menyimpan semua slide presentasi ke sebuah stream dalam format yang ditentukan dengan opsi tambahan. |
| [`save(self, options)`](/slides/python-net/id/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/id/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Menyimpan slide tertentu dari presentasi ke sebuah file dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/id/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Menyimpan slide tertentu dari presentasi ke sebuah file dengan format yang ditentukan sambil mempertahankan nomor halaman. |
| [`save(self, stream, slides, format)`](/slides/python-net/id/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Menyimpan slide tertentu dari presentasi ke sebuah stream dalam format yang ditentukan sambil mempertahankan nomor halaman. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/id/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Menyimpan slide tertentu dari presentasi ke sebuah stream dalam format yang ditentukan sambil mempertahankan nomor halaman. |
| [`get_images(self, options)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Mengembalikan objek Image untuk semua slide presentasi. |
| [`get_images(self, options, slides)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Mengembalikan objek Thumbnail Image untuk slide tertentu dari presentasi. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan skala kustom. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Mengembalikan objek Thumbnail Image untuk slide tertentu dari presentasi dengan skala kustom. |
| [`get_images(self, options, image_size)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Mengembalikan objek Thumbnail Image untuk semua slide presentasi dengan ukuran tertentu. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/id/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Mengembalikan objek Thumbnail Image untuk slide tertentu dari presentasi dengan ukuran tertentu. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/id/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/id/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [`get_slide_by_id(self, id)`](/slides/python-net/id/aspose.slides/presentation/get_slide_by_id/#int) | Mengembalikan Slide, MasterSlide, atau LayoutSlide berdasarkan Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/id/aspose.slides/presentation/join_portions_with_same_formatting/#) | Menggabungkan run dengan format yang sama di semua paragraf dalam semua shape yang dapat diterima di semua slide. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/id/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/id/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/id/aspose.slides/presentation/replace_regex/#str-str) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)