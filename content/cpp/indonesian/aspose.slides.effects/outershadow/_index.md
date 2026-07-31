---
title: OuterShadow
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili efek Outer Shadow.
type: docs
weight: 1041
url: /id/aspose.slides.effects/outershadow/
---
## OuterShadow kelas

Mewakili efek Outer Shadow.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Menentukan apakah [OuterShadow](./) yang ditentukan sama dengan [OuterShadow](./) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan floating point gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius, dalam poin. Nilai default — 0 pt. Baca **double**. |
| **float** [get_Direction](./get_direction/)() override | Arah bayangan, dalam derajat. Nilai default — 0 ° (kiri-ke-kanan). Baca **float**. |
| **double** [get_Distance](./get_distance/)() override | Jarak bayangan dari objek, dalam poin. Nilai default — 0 pt. Baca **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) induk. Hanya-baca [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Penjajaran persegi panjang. Nilai default — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Baca [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Menunjukkan apakah bayangan berputar bersama dengan bentuk. Nilai default — true. Baca **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Faktor skala horizontal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default — 100 %. Baca **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Faktor skala vertikal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default — 100 %. Baca **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Warna bayangan. Nilai default — hitam otomatis (tergantung tema). Hanya-baca [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Sudut miring horizontal, dalam derajat. Nilai default — 0 °. Baca **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Sudut miring vertikal, dalam derajat. Nilai default — 0 °. Baca **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versi. Hanya-baca **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Mendapatkan data efek Outer Shadow yang efektif dengan penerapan pewarisan. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius, dalam poin. Nilai default — 0 pt. Tulis **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Arah bayangan, dalam derajat. Nilai default — 0 ° (kiri-ke-kanan). Tulis **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Jarak bayangan dari objek, dalam poin. Nilai default — 0 pt. Tulis **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Penjajaran persegi panjang. Nilai default — [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Tulis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Menunjukkan apakah bayangan berputar bersama dengan bentuk. Nilai default — true. Tulis **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Faktor skala horizontal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default — 100 %. Tulis **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Faktor skala vertikal, dalam persentase ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default — 100 %. Tulis **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Sudut miring horizontal, dalam derajat. Nilai default — 0 °. Tulis **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Sudut miring vertikal, dalam derajat. Nilai default — 0 °. Tulis **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IOuterShadow](../ioutershadow/)
* Kelas [IVisualEffect](../ivisualeffect/)
* Kelas [IPVIObject](../../aspose.slides/ipviobject/)
* Ruang Nama [Aspose::Slides::Effects](../)
* Pustaka [Aspose.Slides](../../)