---
title: Rotation3D
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili rotasi 3D dari sebuah bagan.
type: docs
weight: 1327
url: /id/aspose.slides.charts/rotation3d/
---
## Rotation3D kelas

Mewakili rotasi 3D dari sebuah bagan.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Mengembalikan kedalaman bagan 3D sebagai persentase lebar bagan (antara 20 dan 2000 persen). Baca **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Menentukan tinggi bagan 3-D sebagai persentase lebar bagan (antara 5 dan 500 persen). Baca **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Mengembalikan nilai perspektif (sudut bidang pandang) untuk bagan 3D (antara 0 dan 240). Diabaikan jika RightAngleAxes property value adalah true. Baca **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Menentukan apakah sumbu bagan berada pada sudut kanan, bukan digambar dalam perspektif. Dengan kata lain menentukan apakah sudut sumbu bagan independen dari rotasi atau elevasi bagan. Baca **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Mengembalikan derajat rotasi sekitar sumbu X, yaitu arah Y untuk bagan 3D (antara -90 dan 90 derajat). Properti ini sesuai dengan item rotX (X Rotation) 21.2.2.157 dalam ECMA-376 dan dengan opsi "Y Rotation" pada PowerPoint 2007+. Baca **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Mengembalikan derajat rotasi sekitar sumbu Y, yaitu arah X untuk bagan 3D (antara 0 dan 360 derajat). Properti ini sesuai dengan item rotY (Y Rotation) 21.2.2.158 dalam ECMA-376 dan dengan opsi "X Rotation" pada PowerPoint 2007+. Baca **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan penggandaan tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Mengatur kedalaman bagan 3D sebagai persentase lebar bagan (antara 20 dan 2000 persen). Tulis **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Menentukan tinggi bagan 3-D sebagai persentase lebar bagan (antara 5 dan 500 persen). Tulis **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Mengatur nilai perspektif (sudut bidang pandang) untuk bagan 3D (antara 0 dan 240). Diabaikan jika RightAngleAxes property value adalah true. Tulis **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Menentukan apakah sumbu bagan berada pada sudut kanan, bukan digambar dalam perspektif. Dengan kata lain menentukan apakah sudut sumbu bagan independen dari rotasi atau elevasi bagan. Tulis **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Mengatur derajat rotasi sekitar sumbu X, yaitu arah Y untuk bagan 3D (antara -90 dan 90 derajat). Properti ini sesuai dengan item rotX (X Rotation) 21.2.2.157 dalam ECMA-376 dan dengan opsi "Y Rotation" pada PowerPoint 2007+. Tulis **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Mengatur derajat rotasi sekitar sumbu Y, yaitu arah X untuk bagan 3D (antara 0 dan 360 derajat). Properti ini sesuai dengan item rotY (Y Rotation) 21.2.2.158 dalam ECMA-376 dan dengan opsi "X Rotation" pada PowerPoint 2007+. Tulis **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menyetel argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembongkaran pernyataan C# lock(). Panggil secara langsung atau gunakan [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IRotation3D](../irotation3d/)
* Kelas [IDOMObject](../../aspose.slides/idomobject/)
* Ruang Nama [Aspose::Slides::Charts](../)
* Perpustakaan [Aspose.Slides](../../)