---
title: ColorFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili warna yang digunakan dalam presentasi.
type: docs
weight: 339
url: /id/aspose.slides/colorformat/
---
## ColorFormat kelas


Mewakili warna yang digunakan dalam presentasi.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Metode

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Salin format warna dari "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Memeriksa kesamaan dengan objek yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **uint8_t** [get_B](./get_b/)() override | Mengembalikan komponen biru dari warna. Semua transformasi warna diabaikan. Baca **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Mengatur warna RGB dan menghapus semua transformasi warna. Baca [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Mengembalikan operasi transformasi warna yang diterapkan pada warna pada indeks yang ditentukan. Baca/tulis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Mengembalikan koleksi transformasi warna yang diterapkan pada sebuah warna. Hanya-baca [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Mengembalikan metode definisi warna. Baca [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Mengembalikan komponen biru dari warna. Semua transformasi warna diabaikan. Baca **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Mengembalikan komponen hijau dari warna. Semua transformasi warna diabaikan. Baca **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Mengembalikan komponen merah dari warna. Semua transformasi warna diabaikan. Baca **float**. |
| **uint8_t** [get_G](./get_g/)() override | Mengembalikan komponen hijau dari warna. Semua transformasi warna diabaikan. |
| **float** [get_Hue](./get_hue/)() override | Mengembalikan komponen hue (warna) dari warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Mengembalikan komponen luminansi dari warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Mengembalikan objek Parent_Immediate. Hanya-baca [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan induk [IPresentationComponent](../ipresentationcomponent/). Hanya-baca [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Mengembalikan preset warna. Baca [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Mengembalikan komponen merah dari warna. Semua transformasi warna diabaikan. Baca **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Mengembalikan komponen saturasi dari warna dalam representasi HSL. Semua transformasi warna diabaikan. Baca **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Mengembalikan warna yang diidentifikasi oleh skema warna. Baca [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Mengembalikan warna yang diidentifikasi oleh tabel warna sistem. Baca [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_B](./set_b/)(**uint8_t**) override | Mengatur komponen biru dari warna. Semua transformasi warna diabaikan. Tulis **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Mengembalikan warna hasil (dengan semua transformasi warna diterapkan). Mengatur warna RGB dan menghapus semua transformasi warna. Tulis [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Mengatur operasi transformasi warna yang diterapkan pada warna pada indeks yang ditentukan. Baca/tulis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Mengatur metode definisi warna. Tulis [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Mengatur komponen biru dari warna. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Mengatur komponen hijau dari warna. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Mengatur komponen merah dari warna. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Mengatur komponen hijau dari warna. Semua transformasi warna diabaikan. |
| void [set_Hue](./set_hue/)(**float**) override | Mengatur komponen hue (warna) dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Mengatur komponen luminansi dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Mengatur preset warna. Tulis [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Mengatur komponen merah dari warna. Semua transformasi warna diabaikan. Tulis **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Mengatur komponen saturasi dalam representasi HSL. Semua transformasi warna diabaikan. Tulis **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Mengatur warna yang diidentifikasi oleh skema warna. Tulis [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Mengatur warna yang diidentifikasi oleh tabel warna sistem. Tulis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Mengembalikan sebuah [System::String](../../system/string/) yang mewakili format warna saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan weak reference. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [PVIObject](../pviobject/)
* Kelas [IColorFormat](../icolorformat/)
* Ruang Nama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)