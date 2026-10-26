---
title: PresentationFactory
second_title: Referensi API Aspose.Slides untuk C++
description: Memungkinkan pembuatan presentasi melalui antarmuka COM
type: docs
weight: 4850
url: /id/aspose.slides/presentationfactory/
---
## PresentationFactory kelas

Allows to create presentation via COM interface

```cpp
class PresentationFactory : public Aspose::Slides::IPresentationFactory
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)() override | Membuat presentasi baru. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [CreatePresentation](./createpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Membuat presentasi baru dengan opsi pemuatan tambahan |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| static [System::SharedPtr](../../system/sharedptr/)\<[PresentationFactory](./)\> [get_Instance](./get_instance/)() | [Presentation](../presentation/) instansi statis pabrik. Hanya-baca [PresentationFactory](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::String](../../system/string/)) override | Membuat objek [PresentationInfo](../presentationinfo/) baru dari file dan mengikat presentasi padanya. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationInfo](../ipresentationinfo/)\> [GetPresentationInfo](./getpresentationinfo/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Membuat objek [PresentationInfo](../presentationinfo/) baru dari aliran dan mengikat presentasi padanya. Mendapatkan informasi tentang presentasi dalam aliran yang ditentukan. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::String](../../system/string/), [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Mengambil teks mentah dari slide |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/)) override | Mengambil teks mentah dari slide |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationText](../ipresentationtext/)\> [GetPresentationText](./getpresentationtext/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [TextExtractionArrangingMode](../textextractionarrangingmode/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Mengambil teks mentah dari slide |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Membaca presentasi yang ada dari array |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Membaca presentasi yang ada dari array dengan opsi pemuatan tambahan |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Membaca presentasi yang ada dari aliran |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/)) override | Membaca presentasi yang ada dari file |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [ReadPresentation](./readpresentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ILoadOptions](../iloadoptions/)\>) override | Membaca presentasi yang ada dari aliran dengan opsi pemuatan tambahan |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan bersama). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

Contoh berikut menunjukkan cara memeriksa Format [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info->get_LoadFormat())); // PPTX
System::SharedPtr<IPresentationInfo> info2 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.ppt");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info2->get_LoadFormat())); // PPT
System::SharedPtr<IPresentationInfo> info3 = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.odp");
System::Console::WriteLine(System::ExplicitCast<System::Object>(info3->get_LoadFormat())); // ODP
```
Contoh berikut menunjukkan cara mendapatkan properti dari [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
System::Console::WriteLine(System::ExplicitCast<System::Object>(props->get_CreatedTime()));
System::Console::WriteLine(props->get_Subject());
System::Console::WriteLine(props->get_Title());
```
Contoh berikut menunjukkan cara memperbarui properti [Presentation](../presentation/). 
```cpp
System::SharedPtr<IPresentationInfo> info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
System::SharedPtr<IDocumentProperties> props = info->ReadDocumentProperties();
props->set_Title(u"My title");
info->UpdateDocumentProperties(props);
```

## Lihat Juga

* Kelas [IPresentationFactory](../ipresentationfactory/)
* Namespace [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)