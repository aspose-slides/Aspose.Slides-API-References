---
title: RSAEncryptionPadding
second_title: Referensi API Aspose.Slides untuk C++
description: Mode padding dan parameter untuk operasi enkripsi atau dekripsi RSA.
type: docs
weight: 482
url: /id/system.security.cryptography/rsaencryptionpadding/
---
## RSAEncryptionPadding kelas

Mode padding dan parameter untuk [RSA](../rsa/) enkripsi atau dekripsi.

```cpp
class RSAEncryptionPadding : public System::IEquatable<SharedPtr<RSAEncryptionPadding>>
```

## Metode

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [CreateOaep](./createoaep/)(const [HashAlgorithmName](../hashalgorithmname/)\&) | Membuat [RSAEncryptionPadding](./) dengan mode OAEP dan algoritma hash yang ditentukan. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\>) override |  |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Menentukan apakah objek saat ini dan objek yang ditentukan sama. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [RSAEncryptionPaddingMode](../rsaencryptionpaddingmode/) [get_Mode](./get_mode/)() const | Mendapatkan mode padding. |
| const [HashAlgorithmName](../hashalgorithmname/)\& [get_OaepHashAlgorithm](./get_oaephashalgorithm/)() const | Mendapatkan algoritma hash yang digunakan dengan OAEP. |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA1](./get_oaepsha1/)() | Mendapatkan mode OAEP dengan algoritma hash [SHA1](../sha1/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA256](./get_oaepsha256/)() | Mendapatkan mode OAEP dengan algoritma hash [SHA256](../sha256/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA384](./get_oaepsha384/)() | Mendapatkan mode OAEP dengan algoritma hash [SHA384](../sha384/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_OaepSHA512](./get_oaepsha512/)() | Mendapatkan mode OAEP dengan algoritma hash [SHA512](../sha512/). |
| static [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](./)\> [get_Pkcs1](./get_pkcs1/)() | Mendapatkan mode PKCS #1 v1.5. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| int [GetHashCode](./gethashcode/)() const override | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan kelas turunan. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan kelas turunan. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan nilai tipe objek dengan nullptr berdasarkan referensi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer menjadi mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IEquatable](../../system/iequatable/)
* Namespace [System::Security::Cryptography](../)
* Pustaka [Aspose.Slides](../../)