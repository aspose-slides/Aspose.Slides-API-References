---
title: IReflection
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili efek refleksi.
type: docs
weight: 937
url: /id/aspose.slides.effects/ireflection/
---
## IReflection kelas

Mewakili efek refleksi.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radius. Baca **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Arah refleksi. Baca **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Jarak refleksi. Baca **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Menentukan posisi akhir (pada lereng gradien alfa) nilai alfa akhir (persen). Baca **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Opasitas refleksi akhir. (persen). Baca **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Menentukan arah pergeseran refleksi. (sudut). Baca **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Penjajaran persegi panjang. Baca [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Menentukan apakah refleksi harus berputar bersama bentuk jika bentuk diputar. Baca **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Menentukan faktor skala horizontal, skala negatif menyebabkan pembalikan. (persen) Baca **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Menentukan faktor skala vertikal, skala negatif menyebabkan pembalikan. (persen) Baca **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Menentukan sudut skew horizontal. Baca **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Menentukan sudut skew vertikal. Baca **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Menentukan posisi awal (pada lereng gradien alfa) nilai alfa awal (persen). Baca **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Opasitas refleksi awal. (persen). Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Mendapatkan data efektif dengan pewarisan yang diterapkan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk penguncian. Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radius. Tulis **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Arah refleksi. Tulis **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Jarak refleksi. Tulis **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Menentukan posisi akhir (pada lereng gradien alfa) nilai alfa akhir (persen). Tulis **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Opasitas refleksi akhir. (persen). Tulis **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Menentukan arah pergeseran refleksi. (sudut). Tulis **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Penjajaran persegi panjang. Tulis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Menentukan apakah refleksi harus berputar bersama bentuk jika bentuk diputar. Tulis **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Menentukan faktor skala horizontal, skala negatif menyebabkan pembalikan. (persen) Tulis **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Menentukan faktor skala vertikal, skala negatif menyebabkan pembalikan. (persen) Tulis **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Menentukan sudut skew horizontal. Tulis **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Menentukan sudut skew vertikal. Tulis **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Menentukan posisi awal (pada lereng gradien alfa) nilai alfa awal (persen). Tulis **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Opasitas refleksi awal. (persen). Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n sebagai weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk [System.Object](../../system/object/) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan lock() C# untuk membuka kunci. Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IImageTransformOperation](../iimagetransformoperation/)
* Kelas [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Ruang Nama [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)