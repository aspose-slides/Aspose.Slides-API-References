---
title: Matrix
second_title: Referensi API Aspose.Slides for C++
description: "Mewakili matriks 3x3 yang mendefinisikan operasi transformasi. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject() . Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 118
url: /id/system.drawing.drawing2d/matrix/
---
## Matrix kelas

Mewakili matriks 3x3 yang mendefinisikan operasi transformasi. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class Matrix : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Membuat salinan dari objek saat ini. |
| void [Dispose](./dispose/)() | Melepaskan semua sumber daya sistem operasi yang diakuisisi oleh objek saat ini. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Menguji apakah objek yang ditentukan adalah [Matrix](./) dan identik dengan objek ini. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Mengembalikan sebuah array yang berisi elemen-elemen matriks dalam urutan berikut: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Menentukan apakah matriks yang direpresentasikan oleh objek saat ini adalah matriks identitas. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Menentukan apakah matriks yang direpresentasikan oleh objek saat ini dapat dibalik. |
| **float** [get_OffsetX](./get_offsetx/)() const | Mengembalikan nilai translasi X dari matriks yang direpresentasikan oleh objek saat ini. |
| **float** [get_OffsetY](./get_offsety/)() const | Mengembalikan nilai translasi Y dari matriks yang direpresentasikan oleh objek saat ini. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Membalikkan matriks yang direpresentasikan oleh objek saat ini. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Membuat instance baru dari kelas [Matrix](./) yang merepresentasikan matriks identitas. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Membuat instance baru dari kelas [Matrix](./) dan menginisialisasinya dengan nilai-nilai yang ditentukan. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Membuat instance baru dari kelas [Matrix](./) untuk transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Membuat instance baru dari kelas [Matrix](./) untuk transformasi geometris yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Mengalikan matriks yang direpresentasikan oleh objek saat ini dengan matriks yang ditentukan. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Mengalikan matriks yang direpresentasikan oleh objek saat ini dengan matriks yang ditentukan. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [Reset](./reset/)() | Mengatur ulang matriks yang direpresentasikan oleh objek saat ini sehingga menjadi matriks identitas. |
| void [Rotate](./rotate/)(**float**) | Memutar matriks yang direpresentasikan oleh objek saat ini searah jarum jam dengan sudut yang ditentukan. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Memutar matriks yang direpresentasikan oleh objek saat ini searah jarum jam sekitar titik origin dengan sudut yang ditentukan. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Memutar matriks yang direpresentasikan oleh objek saat ini searah jarum jam sekitar titik yang ditentukan dengan sudut yang ditentukan. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Memutar matriks yang direpresentasikan oleh objek saat ini searah jarum jam sekitar titik yang ditentukan dengan sudut yang ditentukan. |
| void [Scale](./scale/)(**float**, **float**) | Menerapkan vektor skala yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Menerapkan vektor skala yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan penggantian pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Menerapkan vektor shear yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Menerapkan vektor shear yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan konversi objek kustom ke string. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Menerapkan transformasi geometris yang didefinisikan oleh matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Menerapkan transformasi geometris yang didefinisikan oleh matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Menerapkan transformasi geometris yang didefinisikan oleh matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Menerapkan transformasi geometris yang didefinisikan oleh matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Menerapkan hanya komponen skala dan rotasi dari matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Menerapkan hanya komponen skala dan rotasi dari matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Menerapkan hanya komponen skala dan rotasi dari matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Menerapkan hanya komponen skala dan rotasi dari matriks yang direpresentasikan oleh objek saat ini ke titik-titik yang ditentukan. |
| void [Translate](./translate/)(**float**, **float**) | Menerapkan vektor translasi yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Menerapkan vektor translasi yang ditentukan ke matriks yang direpresentasikan oleh objek saat ini. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentry [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Mengalikan setiap vektor dalam array dengan matriks yang direpresentasikan oleh objek saat ini. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Mengalikan setiap vektor dalam array dengan matriks yang direpresentasikan oleh objek saat ini. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Perpustakaan [Aspose.Slides](../../)