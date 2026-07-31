---
title: SslStream
second_title: Referensi API Aspose.Slides untuk C++
description: Aliran yang menggunakan protokol SSL untuk mengautentikasi server dan secara opsional klien.
type: docs
weight: 14
url: /id/system.net.security/sslstream/
---
## SslStream kelas

Aliran yang menggunakan protokol SSL untuk mengautentikasi server dan secara opsional klien.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Mengautentikasi sisi klien dari koneksi. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Mengautentikasi sisi klien dari koneksi. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Memulai operasi baca asinkron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi baca asinkron. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Memulai operasi tulis asinkron. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Memulai operasi tulis asinkron. |
| void [Close](./close/)() override | Menutup aliran. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Menyalin byte ke aliran yang ditentukan. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Menyalin byte ke aliran yang ditentukan, menggunakan ukuran buffer yang ditentukan. |
| void [Dispose](./dispose/)(**bool**) override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran. |
| void [Dispose](../../system.io/stream/dispose/)() override | Melepaskan semua sumber daya yang digunakan oleh objek saat ini dan menutup aliran. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Menunggu hingga operasi baca asynchronous yang ditentukan selesai. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Menunggu hingga operasi baca asynchronous yang ditentukan selesai. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Mengakhiri operasi tulis asynchronous. Menunggu hingga operasi tulis asynchronous yang ditentukan selesai. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Mengakhiri operasi tulis asynchronous. Menunggu hingga operasi tulis asynchronous yang ditentukan selesai. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| void [Flush](./flush/)() override | Mengosongkan buffer aliran ini dan menulis semua data yang di-buffer ke penyimpanan yang mendasarinya. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous mengosongkan semua buffer untuk aliran ini, menyebabkan semua data yang di-buffer ditulis ke perangkat yang mendasarinya, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Secara asynchronous mengosongkan semua buffer untuk aliran ini, menyebabkan semua data yang di-buffer ditulis ke perangkat yang mendasarinya, dan memantau permintaan pembatalan. |
| **bool** [get_CanRead](./get_canread/)() const override | Menentukan apakah aliran dapat dibaca. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Menentukan apakah aliran mendukung pencarian. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Mendapatkan nilai yang menentukan apakah aliran saat ini dapat waktu habis. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Menentukan apakah aliran dapat ditulis. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Mengembalikan nilai yang menunjukkan apakah daftar pencabutan sertifikat dicek selama proses validasi sertifikat. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Mengembalikan algoritma enkripsi. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Mengembalikan kekuatan algoritma enkripsi yang digunakan. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Mengembalikan algoritma hash. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Mengembalikan kekuatan algoritma hash yang digunakan. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Mengembalikan nilai yang menunjukkan apakah autentikasi berhasil. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Mengembalikan nilai yang menunjukkan apakah data yang dikirim menggunakan aliran ini dienkripsi. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Mengembalikan nilai yang menunjukkan apakah server dan klien telah terautentikasi. |
| **bool** [get_IsServer](./get_isserver/)() const override | Mengembalikan nilai yang menunjukkan apakah sisi lokal koneksi adalah server. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Mengembalikan nilai yang menunjukkan apakah data yang dikirim menggunakan aliran ini ditandatangani. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Mengembalikan kekuatan algoritma pertukaran kunci yang digunakan. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Mengembalikan aliran yang digunakan oleh instance kelas saat ini untuk mengirim dan menerima data. |
| **int64_t** [get_Length](./get_length/)() const override | Mengembalikan panjang aliran dalam byte. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Mengembalikan sertifikat yang digunakan untuk mengautentikasi titik akhir lokal. |
| **int64_t** [get_Position](./get_position/)() const override | Mengembalikan posisi saat ini dari aliran. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba membaca sebelum waktu habis. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Mengembalikan sertifikat yang digunakan untuk mengautentikasi titik akhir remote. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Mengembalikan protokol SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Mendapatkan nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba menulis sebelum waktu habis. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah contoh dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke array byte yang ditentukan. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Membaca sejumlah byte yang ditentukan dari aliran dan menuliskannya ke rentang byte yang ditentukan. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous membaca urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebanyak jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asynchronous membaca urutan byte dari aliran saat ini, memajukan posisi dalam aliran sebanyak jumlah byte yang dibaca, dan memantau permintaan pembatalan. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Membaca satu byte dari aliran dan mengembalikan nilai integer 32-bit yang setara dengan nilai byte yang dibaca. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Mengatur posisi aliran yang diwakili oleh objek saat ini. |
| void [set_Position](./set_position/)(**int64_t**) override | Mengatur posisi aliran. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Mengatur nilai yang menentukan apakah aliran saat ini dapat waktu habis. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Mengatur nilai yang menentukan apakah aliran saat ini dapat waktu habis. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Mengatur nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba membaca sebelum waktu habis. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Mengatur nilai, dalam milidetik, yang menentukan berapa lama aliran akan mencoba membaca sebelum waktu habis. |
| void [SetLength](./setlength/)(**int64_t**) override | Mengatur panjang aliran yang diwakili oleh objek saat ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan beralih pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Membuat sebuah instansi baru. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Membuat sebuah instansi baru. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Membuat sebuah instansi baru. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Membuat sebuah instansi baru. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Membuat sebuah instansi baru. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Menulis array byte yang ditentukan ke aliran. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Menulis array byte yang ditentukan ke aliran. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Menulis subrentang byte yang ditentukan dari rentang byte yang ditentukan ke aliran. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Secara asynchronous menulis urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Secara asynchronous menulis urutan byte ke aliran saat ini, memajukan posisi saat ini dalam aliran ini sebanyak jumlah byte yang ditulis, dan memantau permintaan pembatalan. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Menulis nilai integer tak bertanda 8-bit yang ditentukan ke aliran. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Aliran tanpa penyimpanan yang mendasari. |

## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Tipe AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | Tipe pointer ke implementasi. |

## Lihat Juga

* Kelas [AuthenticatedStream](../authenticatedstream/)
* Ruang nama [System::Net::Security](../)
* Perpustakaan [Aspose.Slides](../../)