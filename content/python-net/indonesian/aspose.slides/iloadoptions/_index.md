---
title: ILoadOptions class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iloadoptions/
---
## ILoadOptions kelas

Allows to specify additional options (such as format or default font) when loading a presentation.

The ILoadOptions type exposes the following members:

## Properti

| Property | Description |
| :- | :- |
| [`load_format`](/slides/python-net/id/aspose.slides/iloadoptions/load_format/) | Mengembalikan atau mengatur format presentasi yang akan dimuat.<br/>            Baca/tulis [`LoadFormat`](/slides/python-net/id/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/id/aspose.slides/iloadoptions/default_regular_font/) | Mengembalikan atau mengatur font Reguler yang digunakan jika font sumber tidak ditemukan.<br/>            Baca-tulis **str**. |
| [`default_symbol_font`](/slides/python-net/id/aspose.slides/iloadoptions/default_symbol_font/) | Mengembalikan atau mengatur font Simbol yang digunakan jika font sumber tidak ditemukan.<br/>            Baca-tulis **str**. |
| [`default_asian_font`](/slides/python-net/id/aspose.slides/iloadoptions/default_asian_font/) | Mengembalikan atau mengatur font Asia yang digunakan jika font sumber tidak ditemukan.<br/>            Baca-tulis **str**. |
| [`password`](/slides/python-net/id/aspose.slides/iloadoptions/password/) | Mendapatkan atau mengatur kata sandi.<br/>            Baca-tulis **str**. |
| [`only_load_document_properties`](/slides/python-net/id/aspose.slides/iloadoptions/only_load_document_properties/) | Properti ini masuk akal bila file presentasi dilindungi kata sandi.<br/>            Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi yang terenkripsi dan kata sandi harus diabaikan.<br/>            Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang benar.<br/>            Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan.<br/>            Jika properti dokumen dari file terenkripsi tidak publik dan nilai properti adalah true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilemparkan.<br/>            Baca-tulis **bool**. |
| [`warning_callback`](/slides/python-net/id/aspose.slides/iloadoptions/warning_callback/) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan.<br/>            Baca/tulis [`IWarningCallback`](/slides/python-net/id/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/id/aspose.slides/iloadoptions/blob_management_options/) | Merepresentasikan opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs),<br/>            seperti penggunaan file sementara atau maksimum byte BLOBs dalam memori. Opsi ini dimaksudkan untuk mengatur<br/>            rasio kinerja/konsumsi memori terbaik untuk lingkungan atau kebutuhan tertentu.<br/>            Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas - yaitu BLOB dapat <br/>            berupa audio, video, atau presentasi itu sendiri. |
| [`document_level_font_sources`](/slides/python-net/id/aspose.slides/iloadoptions/document_level_font_sources/) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi.<br/>            Font ini tersedia untuk presentasi sepanjang masa hidupnya dan tidak dibagikan dengan presentasi lain |
| [`interruption_token`](/slides/python-net/id/aspose.slides/iloadoptions/interruption_token/) | Token untuk memantau permintaan interupsi.<br/>            Token ini mengelola seluruh siklus hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). Setiap operasi yang berjalan lama, seperti pemuatan atau penyimpanan presentasi, akan diinterupsi melalui pemanggilan metode [`IInterruptionTokenSource.interrupt`](/slides/python-net/id/aspose.slides/iinterruptiontokensource/interrupt) dari [`IInterruptionTokenSource`](/slides/python-net/id/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/id/aspose.slides/iloadoptions/resource_loading_callback/) | Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal.<br/>            Baca/tulis [`IResourceLoadingCallback`](/slides/python-net/id/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/id/aspose.slides/iloadoptions/spreadsheet_options/) | Merepresentasikan opsi yang dapat digunakan untuk menentukan perilaku spreadsheet tambahan. |
| [`default_text_language`](/slides/python-net/id/aspose.slides/iloadoptions/default_text_language/) | Mengembalikan atau mengatur bahasa default untuk teks presentasi.<br/>            Baca-tulis **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/id/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang tertanam saat memuat presentasi.<br/>            Jenis-jenis objek biner yang tertanam:<br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/id/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/id/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/id/aspose.slides/icontrol/active_x_control_binary)<br/><br/>Baca-tulis **bool**. |


### Lihat Juga
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)