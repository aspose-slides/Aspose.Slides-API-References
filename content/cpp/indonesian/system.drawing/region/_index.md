---
title: Region
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili interior dari sebuah bentuk grafis. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 261
url: /id/system.drawing/region/
---
## Region kelas

Mewakili interior sebuah bentuk grafis. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class Region : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Mengembalikan salinan dari objek saat ini. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian dari region yang didefinisikan oleh recangle yang ditentukan yang tidak berpotongan dengan region ini. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian dari region yang didefinisikan oleh recangle yang ditentukan yang tidak berpotongan dengan region ini. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian dari region yang didefinisikan oleh jalur yang ditentukan yang tidak berpotongan dengan region ini. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian dari region yang ditentukan yang tidak berpotongan dengan region ini. |
| void [Dispose](./dispose/)() | Melepas semua sumber daya sistem operasi yang diperoleh oleh objek saat ini. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Menentukan apakah region yang ditentukan identik dengan region yang direpresentasikan oleh objek saat ini pada permukaan gambar yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Mensimulasikan perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil pengecualian region yang didefinisikan oleh rectange yang ditentukan darinya. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil pengecualian region yang didefinisikan oleh rectange yang ditentukan darinya. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil pengecualian region yang didefinisikan oleh jalur yang ditentukan darinya. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil pengecualian region yang ditentukan darinya. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Untuk keperluan internal saja. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Mengambil struktur [RectangleF](../rectanglef/) yang mewakili persegi panjang yang membatasi [Region](./) ini pada permukaan gambar objek [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mengambil struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Mengembalikan objek RegionData yang berisi data yang mendefinisikan region yang direpresentasikan oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Mengembalikan array struktur [RectangleF](../rectanglef/) yang mendekati [Region](./) ini setelah transformasi matriks yang ditentukan diterapkan. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengambil tipe aktual dari objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil perpotongan antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil perpotongan antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil perpotongan antara region ini dan region yang didefinisikan oleh jalur yang ditentukan. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil perpotongan antara region ini dan region yang ditentukan. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merepresentasikan sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Menentukan apakah region yang direpresentasikan oleh objek saat ini memiliki interior kosong pada permukaan gambar yang ditentukan. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Menentukan apakah region yang direpresentasikan oleh objek saat ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Menentukan apakah sebagian dari persegi panjang yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Menentukan apakah sebagian dari persegi panjang yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini menggunakan grafis yang ditentukan. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini menggunakan grafis yang ditentukan. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Menentukan apakah sebagian dari persegi panjang yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini menggunakan grafis yang ditentukan. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Menentukan apakah sebagian dari persegi panjang yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini menggunakan grafis yang ditentukan. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Menentukan apakah titik yang ditentukan berada di dalam region yang direpresentasikan oleh objek saat ini menggunakan grafis yang ditentukan. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Menginisialisasi objek saat ini menjadi interior kosong. |
| void [MakeInfinite](./makeinfinite/)() | Menginisialisasi objek region ini menjadi interior tak terbatas. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan cloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk salin subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk salin subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
|  [Region](./region/)() | Membuat instance baru dari kelas [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Membuat instance baru dari kelas [Region](./) yang merepresentasikan region yang didefinisikan oleh persegi panjang yang ditentukan. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Membuat instance baru dari kelas [Region](./) yang merepresentasikan region yang didefinisikan oleh persegi panjang yang ditentukan. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Membuat instance baru dari kelas [Region](./) yang merepresentasikan region yang didefinisikan oleh jalur yang ditentukan. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Membuat instance baru dari kelas [Region](./) yang merepresentasikan region yang didefinisikan oleh objek RegionData yang ditentukan. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan bersama). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mengambil nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambahkan penghitung referensi bersama. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Mengubah region ini dengan matriks yang ditentukan. |
| void [Transform](./transform/)(const SkMatrix\&) | Mengubah region ini dengan matriks yang ditentukan. |
| void [Translate](./translate/)(int, int) | Memindahkan koordinat region sebesar jumlah yang ditentukan. |
| void [Translate](./translate/)(**float**, **float**) | Memindahkan koordinat region sebesar jumlah yang ditentukan. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang didefinisikan oleh persegi panjang yang ditentukan. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang didefinisikan oleh jalur yang ditentukan. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan hasil operasi union antara region ini dan region yang ditentukan. |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan (unlocking) pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambahkan penghitung referensi lemah. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Seharusnya tidak dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian-bagian dari region ini dan region yang didefinisikan oleh recangle yang tidak berpotongan. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian-bagian dari region ini dan region yang didefinisikan oleh recangle yang tidak berpotongan. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian-bagian dari region ini dan region yang didefinisikan oleh jalur yang tidak berpotongan. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Mengganti region yang direpresentasikan oleh objek saat ini dengan bagian-bagian dari region ini dan region yang tidak berpotongan. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
| virtual  [~Region](./~region/)() | Destruktor. |
## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang Nama [System::Drawing](../)
* Pustaka [Aspose.Slides](../../)