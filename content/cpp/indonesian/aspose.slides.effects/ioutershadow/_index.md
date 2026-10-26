---
title: IOuterShadow
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili efek Outer Shadow.
type: docs
weight: 885
url: /id/aspose.slides.effects/ioutershadow/
---
## IOuterShadow kelas

Mewakili efek Outer Shadow.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
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
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) radius, dalam poin. Nilai default \\u2013 0 pt. Baca **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Arah bayangan, dalam derajat. Nilai default \\u2013 0 \\u00B0 (kiri-ke-kanan). Baca **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Jarak bayangan dari objek, dalam poin. Nilai default \\u2013 0 pt. Baca **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Perataan persegi panjang. Nilai default \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Baca [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Menunjukkan apakah bayangan berputar bersama bentuk. Nilai default \\u2013 true. Baca **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Faktor skala horizontal, dalam persen dari ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default \\u2013 100 %. Baca **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Faktor skala vertikal, dalam persen dari ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default \\u2013 100 %. Baca **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Warna bayangan. Nilai default \\u2013 hitam otomatis (tergantung tema). Hanya-baca [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Sudut miring horizontal, dalam derajat. Nilai default \\u2013 0 \\u00B0. Baca **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Sudut miring vertikal, dalam derajat. Nilai default \\u2013 0 \\u00B0. Baca **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Mendapatkan data efektif dengan pewarisan diterapkan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Periksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan pengklonan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruksi salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama dengan nilai yang ditentukan. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) radius, dalam poin. Nilai default \\u2013 0 pt. Tulis **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Arah bayangan, dalam derajat. Nilai default \\u2013 0 \\u00B0 (kiri-ke-kanan). Tulis **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Jarak bayangan dari objek, dalam poin. Nilai default \\u2013 0 pt. Tulis **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Perataan persegi panjang. Nilai default \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Tulis [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Menunjukkan apakah bayangan berputar bersama bentuk. Nilai default \\u2013 true. Tulis **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Faktor skala horizontal, dalam persen dari ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default \\u2013 100 %. Tulis **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Faktor skala vertikal, dalam persen dari ukuran asli. Skala negatif menyebabkan pembalikan. Nilai default \\u2013 100 %. Tulis **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Sudut miring horizontal, dalam derajat. Nilai default \\u2013 0 \\u00B0. Tulis **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Sudut miring vertikal, dalam derajat. Nilai default \\u2013 0 \\u00B0. Tulis **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung weak reference. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung weak reference. Tidak boleh dipanggil langsung; gunakan smart pointers atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [IImageTransformOperation](../iimagetransformoperation/)
* Kelas [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Ruang nama [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)