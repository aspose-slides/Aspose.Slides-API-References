---
title: IRotation3D
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili rotasi 3D dari sebuah diagram.
type: docs
weight: 1171
url: /id/aspose.slides.charts/irotation3d/
---
## IRotation3D kelas


Mewakili rotasi 3D dari sebuah diagram.

```cpp
class IRotation3D : public virtual System::Object
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
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Mengembalikan kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Baca **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Baca **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Mengembalikan nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). Diabaikan jika nilai properti RightAngleAxes adalah true. Baca **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Menentukan apakah sumbu diagram berada pada sudut siku-siku, daripada digambar dalam perspektif. Dengan kata lain, ini menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Baca **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Mengembalikan derajat rotasi sekitar sumbu X, yaitu pada arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.2.157 rotX (Rotasi X) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Baca **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Mengembalikan derajat rotasi sekitar sumbu Y, yaitu pada arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.2.158 rotY (Rotasi Y) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Baca **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instansi dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk penyalinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan konstruk penyalinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Menetapkan kedalaman diagram 3D sebagai persentase lebar diagram (antara 20 dan 2000 persen). Tulis **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Menentukan tinggi diagram 3-D sebagai persentase lebar diagram (antara 5 dan 500 persen). Tulis **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Menetapkan nilai perspektif (sudut bidang pandang) untuk diagram 3D (antara 0 dan 100). Diabaikan jika nilai properti RightAngleAxes adalah true. Tulis **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Menentukan apakah sumbu diagram berada pada sudut siku-siku, bukan digambar dalam perspektif. Dengan kata lain, menentukan apakah sudut sumbu diagram independen dari rotasi atau elevasi diagram. Tulis **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Menetapkan derajat rotasi sekitar sumbu X, yaitu pada arah Y untuk diagram 3D (antara -90 dan 90 derajat). Properti ini cocok dengan item 21.2.2.157 rotX (Rotasi X) dalam ECMA-376 dan dengan opsi "Y Rotation" di PowerPoint 2007+. Tulis **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Menetapkan derajat rotasi sekitar sumbu Y, yaitu pada arah X untuk diagram 3D (antara 0 dan 360 derajat). Properti ini cocok dengan item 21.2.2.158 rotY (Rotasi Y) dalam ECMA-376 dan dengan opsi "X Rotation" di PowerPoint 2007+. Tulis **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n sebagai pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengkonversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
## Lihat Juga

* Kelas [Object](../../system/object/)
* Ruang nama [Aspose::Slides::Charts](../)
* Pustaka [Aspose.Slides](../../)