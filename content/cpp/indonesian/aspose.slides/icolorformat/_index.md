---
title: IColorFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili warna yang digunakan dalam presentasi.
type: docs
weight: 1691
url: /id/aspose.slides/icolorformat/
---
## IColorFormat kelas

Mewakili warna yang digunakan dalam presentasi.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Menyalin format warna dari "color". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang bergaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang bergaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **uint8_t** [get_B](./get_b/)() | Mengembalikan komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Menetapkan warna RGB dan menghapus semua transformasi warna. Baca [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Mengembalikan operasi transformasi warna yang diterapkan pada warna pada indeks yang ditentukan. Baca/tulis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Mengembalikan koleksi transformasi warna yang diterapkan pada sebuah warna. Hanya-baca [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Mengembalikan metode definisi warna. Baca [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Mengembalikan komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Baca **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Mengembalikan komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Mengembalikan komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Mengembalikan komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Baca **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Mengembalikan komponen hue dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Mengembalikan komponen luminansi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Mengembalikan preset warna. Baca [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Mengembalikan komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Baca **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Mengembalikan komponen saturasi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Mengembalikan warna yang diidentifikasi oleh skema warna. Baca [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Mengembalikan warna yang diidentifikasi oleh tabel warna sistem. Baca [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili suatu instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan penggandaan tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apapun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apapun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Menetapkan komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Tulis **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Menetapkan warna RGB dan menghapus semua transformasi warna. Tulis [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Menetapkan operasi transformasi warna yang diterapkan pada warna pada indeks yang ditentukan. Baca/tulis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Menetapkan metode definisi warna. Tulis [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Menetapkan komponen biru dari sebuah warna. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Menetapkan komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Menetapkan komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Menetapkan komponen hijau dari sebuah warna. Semua transformasi warna diabaikan. Tulis **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Menetapkan komponen hue dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Menetapkan komponen luminansi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Menetapkan preset warna. Tulis [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Menetapkan komponen merah dari sebuah warna. Semua transformasi warna diabaikan. Tulis **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Menetapkan komponen saturasi dari sebuah warna dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Menetapkan warna yang diidentifikasi oleh skema warna. Tulis [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Menetapkan warna yang diidentifikasi oleh tabel warna sistem. Tulis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Mengembalikan sebuah [System::String](../../system/string/) yang mewakili format warna saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IFillParamSource](../ifillparamsource/)
* Ruang nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)