---
title: BoxedValue
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili nilai terbungkus. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk mengirimnya ke fungsi sebagai argumen."
type: docs
weight: 105
url: /id/system/boxedvalue/
---
## BoxedValue kelas

Mewakili nilai terbungkus. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../smartptr/) dan gunakan pointer ini untuk mengirimnya ke fungsi sebagai argumen.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Type of the boxed value represented by the class |

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | Membuat objek yang mewakili nilai terbungkus yang ditentukan. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Menentukan kesamaan nilai terbungkus yang diwakili oleh objek saat ini dan objek yang ditentukan. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| int [GetHashCode](./gethashcode/)() const override | Mengembalikan kode hash untuk objek saat ini. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Mendapatkan tipe sebenarnya dari objek. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | Mengembalikan nilai yang mewakili tipe nilai terbungkus yang diwakili oleh objek saat ini. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Mengembalikan nilai numerik dari objek terbungkus jika dapat di-cast, sebaliknya mengembalikan nol. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator 'is' C#. |
| **bool** [is](./is/)() const | Menentukan apakah tipe nilai terbungkus yang diwakili oleh objek saat ini adalah **V**. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | Menentukan apakah objek saat ini mewakili nilai terbungkus dari tipe enum. |
| void [Lock](../object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan subclass. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Membungkus nilai konstanta enumerasi dari enumerasi yang ditentukan dengan nama yang ditentukan. Sebuah parameter menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan string yang menentukan nama konstanta enumerasi. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | Membungkus nilai konstanta enumerasi dari enumerasi yang ditentukan dengan nama yang ditentukan. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spesialisasi [Object::ReferenceEquals](../object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Mengonversi nilai terbungkus yang diwakili oleh objek saat ini menjadi string. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | Mengonversi objek terbungkus menjadi string menggunakan string format yang ditentukan. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Melepaskan nilai yang diwakili oleh objek saat ini. |
| void [Unlock](../object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [BoxedValueBase](../boxedvaluebase/)
* Ruangnama [System](../)
* Perpustakaan [Aspose.Slides](../../)