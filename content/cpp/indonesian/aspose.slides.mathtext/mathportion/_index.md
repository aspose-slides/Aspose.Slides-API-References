---
title: MathPortion
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili bagian dengan konteks matematika di dalamnya.
type: docs
weight: 1041
url: /id/aspose.slides.mathtext/mathportion/
---
## MathPortion kelas

Mewakili sebuah bagian dengan konteks matematika di dalamnya.

```cpp
class MathPortion : public Aspose::Slides::Portion,
                    public Aspose::Slides::MathText::IMathPortion
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AddField](../../aspose.slides/portion/addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../../aspose.slides/ifieldtype/)\>) override | Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis. |
| void [AddField](../../aspose.slides/portion/addfield/)([System::String](../../system/string/)) override | Mengonversi bagian ini menjadi bidang yang diperbarui secara otomatis. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../../aspose.slides/ifield/)\> [get_Field](../../aspose.slides/portion/get_field/)() override | Mengembalikan bidang dari bagian ini. Hanya-baca [IField](../../aspose.slides/ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathParagraph](../imathparagraph/)\> [get_MathParagraph](./get_mathparagraph/)() override | Paragraf matematika |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../../aspose.slides/iportionformat/)\> [get_PortionFormat](../../aspose.slides/portion/get_portionformat/)() override | Mengembalikan objek pemformatan yang berisi properti format yang diatur secara eksplisit pada bagian teks tanpa pewarisan yang diterapkan. Hanya-baca [IPortionFormat](../../aspose.slides/iportionformat/). |
| [System::String](../../system/string/) [get_Text](../../aspose.slides/portion/get_text/)() override | Mendapatkan teks biasa dari sebuah bagian. Baca [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](../../aspose.slides/portion/getcoordinates/)() override | Mendapatkan koordinat awal bagian. Koordinat X dari titik mewakili awal bagian dari karakter pertama termasuk bearing sisi kiri. Koordinat Y termasuk bearing sisi atas. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](../../aspose.slides/portion/getrect/)() override | Mendapatkan koordinat persegi panjang yang membatasi bagian. Persegi panjang mencakup semua baris teks dalam bagian, termasuk yang kosong. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan [LockContext](../../system/lockcontext/) sentry object. |
|  [MathPortion](./mathportion/)() | Menginisialisasi instance baru dari kelas [MathPortion](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan penggandaan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
|  [Portion](../../aspose.slides/portion/portion/)() | Menginisialisasi instance baru dari kelas [Portion](../../aspose.slides/portion/). |
|  [Portion](../../aspose.slides/portion/portion/)([System::String](../../system/string/)) | Menginisialisasi instance baru dari kelas [Portion](../../aspose.slides/portion/). |
|  [Portion](../../aspose.slides/portion/portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](../../aspose.slides/portion/)\>) | Menginisialisasi instance baru dari kelas [Portion](../../aspose.slides/portion/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [RemoveField](../../aspose.slides/portion/removefield/)() override | Mengonversi bagian bidang ini menjadi bagian sederhana. |
| void [set_Text](../../aspose.slides/portion/set_text/)([System::String](../../system/string/)) override | Mengatur teks biasa dari sebuah bagian. Tulis [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Catatan

Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Lihat Juga

* Kelas [Portion](../../aspose.slides/portion/)
* Kelas [IMathPortion](../imathportion/)
* Ruang nama [Aspose::Slides::MathText](../)
* Perpustakaan [Aspose.Slides](../../)