---
title: ConnectorLock
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan operasi mana yang dinonaktifkan pada induk Connector.
type: docs
weight: 495
url: /id/aspose.slides/connectorlock/
---
## ConnectorLock kelas

Menentukan operasi mana yang dinonaktifkan pada induk [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## Metode

| Method | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Menentukan apakah mengubah nilai penyesuaian dilarang. Baca **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Menentukan apakah mengubah kepala panah dilarang. Baca **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Menentukan apakah bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Baca **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Baca **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Menentukan apakah menambahkan bentuk ini ke grup dilarang. Baca **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Mengembalikan true jika semua flag kunci dinonaktifkan. **bool** hanya-baca. |
| **bool** [get_PositionMove](./get_positionmove/)() override | Menentukan apakah memindahkan bentuk ini dilarang. Baca **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Menentukan apakah mengubah sudut rotasi bentuk ini dilarang. Baca **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Menentukan apakah memilih bentuk ini dilarang. Baca **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Menentukan apakah mengubah tipe bentuk dilarang. Baca **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Menentukan apakah mengubah ukuran bentuk ini dilarang. Baca **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Memungkinkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instansi dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Menentukan apakah mengubah nilai penyesuaian dilarang. Tulis **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Menentukan apakah mengubah kepala panah dilarang. Tulis **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Menentukan apakah bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Tulis **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Tulis **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Menentukan apakah menambahkan bentuk ini ke grup dilarang. Tulis **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | Menentukan apakah memindahkan bentuk ini dilarang. Tulis **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Menentukan apakah mengubah sudut rotasi bentuk ini dilarang. Tulis **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Menentukan apakah memilih bentuk ini dilarang. Tulis **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Menentukan apakah mengubah tipe bentuk dilarang. Tulis **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Menentukan apakah mengubah ukuran bentuk ini dilarang. Tulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Atur argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengonversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; sebaliknya, gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [BaseShapeLock](../baseshapelock/)
* Kelas [IConnectorLock](../iconnectorlock/)
* RuangNama [Aspose::Slides](../)
* Perpustakaan [Aspose.Slides](../../)