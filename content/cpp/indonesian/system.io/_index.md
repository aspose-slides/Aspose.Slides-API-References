---
title: "System::IO"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 573
url: /id/system.io/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) | Menampilkan pembungkus mirip [System.IO.Stream](./stream/) untuk std::basic_iostream dan objek turunannya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) | Menampilkan pembungkus mirip [System.IO.Stream](./stream/) untuk std::basic_istream dan objek turunannya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) | Menampilkan pembungkus mirip [System.IO.Stream](./stream/) untuk std::basic_ostream dan objek turunannya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) | Menampilkan buffer yang membungkus aliran mirip [System::IO::Stream](./stream/) dan memungkinkan mereka digunakan sebagai buffer internal aliran mirip std::iostream. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) | Menampilkan pembungkus mirip std::iostream yang menggunakan [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) sebagai buffer internal. |
| [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) | Menampilkan pembungkus mirip std::istream yang menggunakan [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) sebagai buffer internal. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) | Menampilkan pembungkus mirip std::ostream yang menggunakan [BasicSystemIOStreamBuf](./basicsystemiostreambuf/) sebagai buffer internal. |
| [BinaryReader](./binaryreader/) | Menampilkan pembaca yang membaca tipe data primitif sebagai data biner dalam enkoding tertentu. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [BinaryWriter](./binarywriter/) | Menampilkan penulis yang menulis nilai tipe primitif ke aliran byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [BufferedStream](./bufferedstream/) | Menambahkan lapisan buffering di atas aliran lain. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [Details_DirectoryNotFoundException](./details_directorynotfoundexception/) |  |
| [Details_DriveNotFoundException](./details_drivenotfoundexception/) |  |
| [Details_EndOfStreamException](./details_endofstreamexception/) |  |
| [Details_FileLoadException](./details_fileloadexception/) |  |
| [Details_FileNotFoundException](./details_filenotfoundexception/) | Pengecualian yang dilemparkan ketika percobaan mengakses file yang tidak ada di disk gagal. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas FileNotFoundException sebagai gantinya. Jangan pernah membungkus instance kelas FileNotFoundException ke dalam [System::SmartPtr](../system/smartptr/). |
| [Details_InvalidDataException](./details_invaliddataexception/) |  |
| [Details_IOException](./details_ioexception/) |  |
| [Details_PathTooLongException](./details_pathtoolongexception/) |  |
| [Directory](./directory/) | Berisi metode untuk memanipulasi direktori. Ini adalah tipe statik tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun. |
| [DirectoryInfo](./directoryinfo/) | Menampilkan jalur sistem file, sebuah direktori yang direferensikan oleh jalur ini dan menyediakan metode instance untuk memanipulasi direktori. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [File](./file/) | Menyediakan metode untuk memanipulasi file. Ini adalah tipe statik tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun. |
| [FileInfo](./fileinfo/) | Menampilkan jalur ke sebuah file dan file yang direferensikan oleh jalur ini serta menyediakan metode untuk memanipulasinya. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [FileStream](./filestream/) | Menampilkan aliran file yang mendukung operasi baca dan tulis sinkron serta asinkron. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [FileSystemInfo](./filesysteminfo/) | Kelas dasar untuk [FileInfo](./fileinfo/) dan [DirectoryInfo](./directoryinfo/). Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [FileSystemInfoStat](./filesysteminfostat/) | Menampilkan informasi tentang sebuah file atau direktori. |
| [MemoryStream](./memorystream/) | Menampilkan aliran yang membaca dari dan menulis ke memori. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [Path](./path/) | Menyediakan metode untuk memanipulasi jalur. Ini adalah tipe statik tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apapun. |
| [STDIOStreamWrapperBase](./stdiostreamwrapperbase/) | Menampilkan kelas dasar untuk pembungkus mirip [System.IO.Stream](./stream/). Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [Stream](./stream/) | Kelas dasar untuk berbagai implementasi aliran. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [StreamReader](./streamreader/) | Menampilkan pembaca yang membaca karakter dari aliran byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [StreamWriter](./streamwriter/) | Menampilkan penulis yang menulis karakter ke aliran byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [StringReader](./stringreader/) | Menampilkan pembaca yang membaca karakter dari string. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [StringWriter](./stringwriter/) | Mengimplementasikan [TextWriter](./textwriter/) yang menulis informasi ke string. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [TextReader](./textreader/) | Kelas dasar untuk kelas yang mewakili pembaca yang membaca urutan karakter dari sumber yang berbeda. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [TextWriter](./textwriter/) | Kelas dasar untuk kelas yang mewakili penulis yang menulis urutan karakter ke tujuan yang berbeda. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [UnmanagedMemoryStream](./unmanagedmemorystream/) | Menyediakan akses ke memori tidak terkelola. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu jalankan dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_istream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Fungsi pembungkus untuk aliran mirip std::basic_istream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_ostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/)) | Fungsi pembungkus untuk aliran mirip std::basic_ostream. |
| [SharedPtr](../system/sharedptr/)\<[Stream](./stream/)\> [WrapSTDIOStream](./wrapstdiostream/)(std::basic_iostream\<char_type, traits_type\>\&, [STDIOStreamWrappingMode](./stdiostreamwrappingmode/), [STDIOStreamPositionPreference](./stdiostreampositionpreference/)) | Fungsi pembungkus untuk aliran mirip std::basic_iostream. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [FileAccess](./fileaccess/) | Menentukan tipe akses saat membuka file. |
| [FileAttributes](./fileattributes/) | Mewakili atribut sebuah direktori atau file. |
| [FileMode](./filemode/) | Menentukan cara file harus dibuka. |
| [FileOptions](./fileoptions/) | Mewakili opsi lanjutan untuk membuat objek [FileStream](./filestream/). |
| [FileShare](./fileshare/) | Menentukan jenis akses apa yang dapat dimiliki objek [FileStream](./filestream/) lain ke file yang sedang dibuka. |
| [SearchOption](./searchoption/) | Menentukan apakah pencarian harus dilakukan hanya di direktori saat ini, atau di direktori saat ini dan semua subdirektorinya. |
| [SeekOrigin](./seekorigin/) | Menentukan posisi referensi dalam aliran relatif terhadap posisi yang akan dicari. |
| [STDIOStreamWrappingMode](./stdiostreamwrappingmode/) | Menentukan mode operasi I/O yang akan dilakukan pembungkus pada aliran mirip std::iostreams. |
| [STDIOStreamPositionPreference](./stdiostreampositionpreference/) | Menentukan posisi mana dalam aliran yang lebih disukai sebagai posisi baca-tulis bersama ketika std::basic_iostream dan keturunannya memiliki posisi baca dan tulis yang berbeda pada saat pembuatan pembungkus. |
| [SystemIOStreamWrappingMode](./systemiostreamwrappingmode/) | Menentukan mode operasi I/O yang akan dilakukan pembungkus pada aliran mirip [System::IO::Stream](./stream/). |
## TipeAlias

| TipeAlias | Deskripsi |
| --- | --- |
| [IOException](./ioexception/) |  |
| [EndOfStreamException](./endofstreamexception/) |  |
| [InvalidDataException](./invaliddataexception/) |  |
| [DirectoryNotFoundException](./directorynotfoundexception/) |  |
| [FileLoadException](./fileloadexception/) |  |
| [PathTooLongException](./pathtoolongexception/) |  |
| [DriveNotFoundException](./drivenotfoundexception/) |  |
| [BinaryWriterPtr](./binarywriterptr/) | Alias untuk shared pointer ke kelas ini. |
| [FileNotFoundException](./filenotfoundexception/) | Pengecualian yang dilemparkan ketika percobaan mengakses file yang tidak ada di disk gagal. Jangan pernah membungkus instance kelas FileNotFoundException ke dalam [System::SmartPtr](../system/smartptr/). |
| [STDIStreamWrapper](./stdistreamwrapper/) | Spesialisasi [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) untuk tipe karakter char. |
| [STDWIStreamWrapper](./stdwistreamwrapper/) | Spesialisasi [BasicSTDIStreamWrapper](./basicstdistreamwrapper/) untuk tipe karakter **wchar_t**. |
| [STDOStreamWrapper](./stdostreamwrapper/) | Spesialisasi [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) untuk tipe karakter char. |
| [STDWOStreamWrapper](./stdwostreamwrapper/) | Spesialisasi [BasicSTDOStreamWrapper](./basicstdostreamwrapper/) untuk tipe karakter **wchar_t**. |
| [STDIOStreamWrapper](./stdiostreamwrapper/) | Spesialisasi [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) untuk tipe karakter char. |
| [STDWIOStreamWrapper](./stdwiostreamwrapper/) | Spesialisasi [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/) untuk tipe karakter **wchar_t**. |
| [SystemIStreamWrapper](./systemistreamwrapper/) | Spesialisasi [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) untuk tipe karakter char. |
| [SystemWIStreamWrapper](./systemwistreamwrapper/) | Spesialisasi [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/) untuk tipe karakter **wchar_t**. |
| [SystemOStreamWrapper](./systemostreamwrapper/) | Spesialisasi [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) untuk tipe karakter char. |
| [SystemWOStreamWrapper](./systemwostreamwrapper/) | Spesialisasi [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/) untuk tipe karakter **wchar_t**. |
| [SystemIOStreamWrapper](./systemiostreamwrapper/) | Spesialisasi [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) untuk tipe karakter char. |
| [SystemWIOStreamWrapper](./systemwiostreamwrapper/) | Spesialisasi [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/) untuk tipe karakter **wchar_t**. |