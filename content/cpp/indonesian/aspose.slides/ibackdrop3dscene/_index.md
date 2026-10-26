---
title: IBackdrop3DScene
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan sebuah bidang di mana efek, seperti cahaya bersinar dan bayangan, diterapkan relatif terhadap bentuk yang menjadi target penerapannya.
type: docs
weight: 1392
url: /id/aspose.slides/ibackdrop3dscene/
---
## IBackdrop3DScene kelas

Mendefinisikan sebuah bidang di mana efek, seperti cahaya bersinar dan bayangan, diterapkan relatif terhadap bentuk yang menjadi target penerapannya.

```cpp
class IBackdrop3DScene : public virtual System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_AnchorPoint](./get_anchorpoint/)() | Mengembalikan sebuah titik dalam ruang 3D. Titik ini adalah titik dalam ruang yang menjadi jangkar bidang latar belakang. Titik 3D direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Baca **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_NormalVector](./get_normalvector/)() | Mengembalikan sebuah vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Baca **float**[]. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_UpVector](./get_upvector/)() | Mengembalikan sebuah vektor yang menggambarkan arah atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang menunjukkan arah atas relatif terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Baca **float**[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan pengklonan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AnchorPoint](./set_anchorpoint/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Menetapkan sebuah titik dalam ruang 3D. Titik ini adalah titik dalam ruang yang menjadi jangkar bidang latar belakang. Titik 3D direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Tulis **float**[]. |
| virtual void [set_NormalVector](./set_normalvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Menetapkan sebuah vektor normal. Lebih tepatnya, atribut ini mendefinisikan vektor yang tegak lurus terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Tulis **float**[]. |
| virtual void [set_UpVector](./set_upvector/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Menetapkan sebuah vektor yang menggambarkan arah atas. Lebih tepatnya, atribut ini mendefinisikan vektor yang menunjukkan arah atas relatif terhadap bidang latar belakang. Vektor direpresentasikan oleh array berisi 3 nilai **float** yang mendefinisikan koordinat X, Y, dan Z. Tulis **float**[]. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai terkini penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi weak. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi weak. Tidak seharusnya dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)