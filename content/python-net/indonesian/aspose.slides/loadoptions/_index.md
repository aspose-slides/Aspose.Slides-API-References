---
title: LoadOptions class
second_title: Aspose.Slides untuk Python via .NET API Referensi
description: 
type: docs
url: /id/aspose.slides/loadoptions/
---
## LoadOptions kelas

Memungkinkan untuk menentukan opsi tambahan (seperti format atau font default) saat memuat sebuah presentasi.

Tipe LoadOptions menampilkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides/loadoptions/__init__/#) | Membuat opsi muat default baru. |
| [`__init__(self, load_format)`](/slides/python-net/id/aspose.slides/loadoptions/__init__/#loadformat) | Membuat opsi muat baru. |

## Properti

| Properti | Deskripsi |
| :- | :- |
| [`load_format`](/slides/python-net/id/aspose.slides/loadoptions/load_format/) | Mengembalikan atau mengatur format presentasi yang akan dimuat.<br/>            Baca/tulis [`LoadFormat`](/slides/python-net/id/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides/loadoptions/default_regular_font/) | Mengembalikan atau mengatur font Reguler yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`default_symbol_font`](/slides/python-net/id/aspose.slides/loadoptions/default_symbol_font/) | Mengembalikan atau mengatur font Simbol yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`default_asian_font`](/slides/python-net/id/aspose.slides/loadoptions/default_asian_font/) | Mengembalikan atau mengatur font Asia yang digunakan bila font sumber tidak ditemukan.<br/>            Baca/tulis **str**. |
| [`password`](/slides/python-net/id/aspose.slides/loadoptions/password/) | Mengambil atau mengatur kata sandi.<br/>            Baca/tulis **str**. |
| [`only_load_document_properties`](/slides/python-net/id/aspose.slides/loadoptions/only_load_document_properties/) | Properti ini masuk akal jika file presentasi dilindungi kata sandi.<br/>            Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi yang terenkripsi dan kata sandi harus diabaikan.<br/>            Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang benar.<br/>            Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan.<br/>            Jika properti dokumen dari file terenkripsi tidak bersifat publik dan nilai properti adalah true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilemparkan.<br/>            Baca/tulis **bool**. |
| [`warning_callback`](/slides/python-net/id/aspose.slides/loadoptions/warning_callback/) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dihentikan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/id/aspose.slides/loadoptions/blob_management_options/) | Mewakili opsi-opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs dalam memori. Opsi-opsi ini ditujukan untuk mengatur rasio kinerja/konsumsi memori terbaik untuk lingkungan atau persyaratan tertentu. Binary Large Object (BLOB) adalah data biner yang disimpan sebagai entitas tunggal — yaitu BLOB dapat berupa audio, video, atau presentasi itu sendiri. |
| [`document_level_font_sources`](/slides/python-net/id/aspose.slides/loadoptions/document_level_font_sources/) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi.<br/>            Font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lain |
| [`interruption_token`](/slides/python-net/id/aspose.slides/loadoptions/interruption_token/) | Token untuk memantau permintaan interupsi.<br/>            <br/>            Token ini mengelola seluruh siklus hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). Operasi yang memakan waktu lama, seperti memuat atau menyimpan presentasi, akan diinterupsi dengan memanggil metode [`InterruptionTokenSource.interrupt`](/slides/python-net/id/aspose.slides/interruptiontokensource/interrupt) dari [`InterruptionTokenSource`](/slides/python-net/id/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/id/aspose.slides/loadoptions/resource_loading_callback/) | Mengembalikan atau mengatur antarmuka panggilan balik yang mengelola pemuatan sumber daya eksternal.<br/>            Baca/tulis [`IResourceLoadingCallback`](/slides/python-net/id/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/id/aspose.slides/loadoptions/spreadsheet_options/) | Mengambil opsi untuk spreadsheet. Misalnya, opsi ini memengaruhi perhitungan rumus untuk grafik. |
| [`default_text_language`](/slides/python-net/id/aspose.slides/loadoptions/default_text_language/) | Mengembalikan atau mengatur bahasa default untuk teks presentasi.<br/>             Baca/tulis **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/id/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat memuat presentasi.<br/>            <br/>Jenis-jenis objek biner tersemat:<br/><br/><br/>* Proyek VBA [`IPresentation.vba_project`](/slides/python-net/id/aspose.slides/ipresentation/vba_project)<br/>* Data tersemat OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* Data biner ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/id/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Baca/tulis **bool**. |

### Lihat Juga
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)