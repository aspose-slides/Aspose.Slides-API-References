---
title: Reflection
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili efek Reflection.
type: docs
weight: 1067
url: /id/aspose.slides.effects/reflection/
---
## Kelas Reflection

Mewakili efek [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Menentukan apakah [Reflection](./) yang ditentukan sama dengan [Reflection](./) saat ini. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan floating point gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius. Baca **double**. |
| **float** [get_Direction](./get_direction/)() override | Arah refleksi. Baca **float**. |
| **double** [get_Distance](./get_distance/)() override | Jarak refleksi. Baca **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Menentukan posisi akhir (sepanjang lereng gradien alfa) dari nilai alfa akhir (persen). Baca **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Opacity akhir refleksi. (persen). Baca **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Menentukan arah offset refleksi. (sudut). Baca **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) induk. [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) hanya-baca. |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Penjajaran persegi panjang. Baca [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Menentukan apakah refleksi harus berputar bersama bentuk bila bentuk diputar. Baca **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Menentukan faktor skala horizontal, skala negatif menyebabkan pembalikan. (persen) Baca **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Menentukan faktor skala vertikal, skala negatif menyebabkan pembalikan. (persen) Baca **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Menentukan sudut skew horizontal. Baca **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Menentukan sudut skew vertikal. Baca **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Menentukan posisi awal (sepanjang lereng gradien alfa) dari nilai alfa awal (persen). Baca **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Opacity awal refleksi. (persen). Baca **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Versi. **uint32_t** hanya-baca. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Mendapatkan data efek [Reflection](./) yang efektif dengan pewarisan diterapkan. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius. Tulis **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Arah refleksi. Tulis **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Jarak refleksi. Tulis **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Menentukan posisi akhir (sepanjang lereng gradien alfa) dari nilai alfa akhir (persen). Tulis **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Opacity akhir refleksi. (persen). Tulis **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Menentukan arah offset refleksi. (sudut). Tulis **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Penjajaran persegi panjang. Tulis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Menentukan apakah refleksi harus berputar bersama bentuk bila bentuk diputar. Tulis **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Menentukan faktor skala horizontal, skala negatif menyebabkan pembalikan. (persen) Tulis **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Menentukan faktor skala vertikal, skala negatif menyebabkan pembalikan. (persen) Tulis **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Menentukan sudut skew horizontal. Tulis **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Menentukan sudut skew vertikal. Tulis **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Menentukan posisi awal (sepanjang lereng gradien alfa) dari nilai alfa awal (persen). Tulis **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Opacity awal refleksi. (persen). Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Class [IReflection](../ireflection/)
* Class [IVisualEffect](../ivisualeffect/)
* Class [IPVIObject](../../aspose.slides/ipviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)