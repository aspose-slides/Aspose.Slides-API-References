---
title: DigitalSignature
second_title: Referensi API Aspose.Slides untuk C++
description: Tanda tangan digital dalam file yang ditandatangani.
type: docs
weight: 768
url: /id/aspose.slides/digitalsignature/
---
## DigitalSignature kelas

Tanda tangan digital dalam file yang ditandatangani.

```cpp
class DigitalSignature : public Aspose::Slides::IDigitalSignature
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [DigitalSignature](./digitalsignature/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>) | Membuat objek [DigitalSignature](./) baru dengan sertifikat yang ditentukan. |
|  [DigitalSignature](./digitalsignature/)([System::String](../../system/string/), [System::String](../../system/string/)) | Membuat objek [DigitalSignature](./) baru dengan jalur file sertifikat dan kata sandi yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\> [get_Certificate](./get_certificate/)() override | Objek sertifikat yang digunakan untuk menandatangani dokumen. Hanya baca [X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Tujuan tanda tangan. Baca [System::String](../../system/string/). |
| **bool** [get_IsValid](./get_isvalid/)() override | Jika tanda tangan digital ini valid dan dokumen tidak diubah, nilai ini akan true. Hanya baca **bool**. |
| [System::DateTime](../../system/datetime/) [get_SignTime](./get_signtime/)() override | Waktu ketika dokumen ditandatangani. Hanya baca [System::DateTime](../../system/datetime/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Periksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Tujuan tanda tangan. Tulis [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Atur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

Contoh berikut menunjukkan cara menambahkan tanda tangan digital dari sertifikat PFX di PowerPoint [Presentation](../presentation/).
```cpp
// Inisialisasi instance Presentation
auto pres = System::MakeObject<Presentation>();

// Buat objek DigitalSignature dengan file PFX dan kata sandi PFX
System::SharedPtr<DigitalSignature> signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
// Komentar tanda tangan digital baru
signature->set_Comments(u"Aspose.Slides digital signing test.");
// Tambahkan tanda tangan digital ke presentasi
pres->get_DigitalSignatures()->Add(signature);
// Simpan presentasi
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```
 Contoh kode berikut menunjukkan cara memvalidasi tanda tangan digital PowerPoint [Presentation](../presentation/).
```cpp
// Inisialisasi instance Presentation
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");

if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;
    System::Console::WriteLine(u"Signatures used to sign the presentation: ");
    // Periksa apakah semua tanda tangan digital valid
    for (auto&& signature : System::IterateOver(pres->get_DigitalSignatures()))
    {
        System::Console::WriteLine(signature->get_Certificate()->get_SubjectName()->get_Name() + u", " +
                                   signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm") + u" -- " +
                                   (signature->get_IsValid() ? System::String(u"VALID") : System::String(u"INVALID")));
        allSignaturesAreValid &= signature->get_IsValid();
    }

    if (allSignaturesAreValid)
    {
        System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
    }
    else
    {
        System::Console::WriteLine(u"Presentation has been modified since signing.");
    }
}
```

## Lihat Juga

* Kelas [IDigitalSignature](../idigitalsignature/)
* Ruang nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)