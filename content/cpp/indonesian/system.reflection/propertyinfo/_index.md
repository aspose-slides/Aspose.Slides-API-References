---
title: PropertyInfo
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili informasi properti.
type: docs
weight: 144
url: /id/system.reflection/propertyinfo/
---
## PropertyInfo kelas

Mewakili informasi properti.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | Menambahkan atribut ke koleksi. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | Mendapatkan tipe deklarasi. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | Mendapatkan nama lengkap anggota. Bisa berbeda dalam bagian yang diimplementasikan secara manual. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | Mendapatkan nilai MemberTypes yang menunjukkan bahwa anggota ini adalah properti. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | Mendapatkan nama anggota. |
| [TypeInfo](../../system/typeinfo/) [get_PropertyType](./get_propertytype/)() | Mendapatkan tipe properti. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | Mendapatkan tipe tipe yang dipantulkan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | Mengembalikan array yang berisi objek-objek yang mewakili semua atribut kustom yang diterapkan pada tipe yang diwakili oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | Mengembalikan array yang berisi objek-objek yang mewakili semua atribut kustom yang diterapkan pada tipe yang diwakili oleh objek saat ini. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Mendapatkan nilai properti dari objek tertentu. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Mendapatkan nilai properti dari objek tertentu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Konstruktor. Properti dengan hanya getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Konstruktor. Properti dengan hanya getter non-const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Konstruktor. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)()) | Konstruktor. Properti [Nullable](../../system/nullable/) dengan setter dan getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)() const) | Konstruktor. Properti [Nullable](../../system/nullable/) dengan hanya getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Konstruktor. Properti [Object](../../system/object/) dengan hanya getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)()) | Membuat informasi properti string. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)() const) | Membuat informasi properti string dari kelas dengan getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)()) | Membuat informasi properti [Decimal](../../system/decimal/). |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)() const) | Membuat informasi properti [Decimal](../../system/decimal/) dari kelas dengan getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)()) | Membuat informasi properti boolean. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)() const) | Membuat informasi properti boolean dari kelas dengan getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)()) | Membuat informasi properti **int64_t**. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)() const) | Membuat informasi properti **int64_t** dari kelas dengan getter const. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [set_PropertyType](./set_propertytype/)(const [TypeInfo](../../system/typeinfo/)\&) | Mengatur tipe properti ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi pointer lemah (bukan bersama). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Mengatur nilai properti ke objek tertentu. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Mengatur nilai properti ke objek tertentu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [MemberInfo](../memberinfo/)
* Ruang Nama [System::Reflection](../)
* Pustaka [Aspose.Slides](../../)