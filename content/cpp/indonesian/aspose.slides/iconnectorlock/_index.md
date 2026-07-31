---
title: IConnectorLock
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan operasi mana yang dinonaktifkan pada Connector induk.
type: docs
weight: 1860
url: /id/aspose.slides/iconnectorlock/
---
## IConnectorLock kelas

Menentukan operasi mana yang dinonaktifkan pada induk [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dalam gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apapun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Menentukan apakah perubahan nilai penyesuaian dilarang. Baca **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Menentukan apakah perubahan kepala panah dilarang. Baca **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Menentukan apakah bentuk harus mempertahankan rasio aspek saat diubah ukuran. Baca **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Menentukan apakah penambahan bentuk ini ke grup dilarang. Baca **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Mengembalikan true jika semua flag penguncian dinonaktifkan. Baca-saja **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Menentukan apakah memindahkan bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Menentukan apakah perubahan sudut rotasi bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Menentukan apakah pemilihan bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Menentukan apakah perubahan tipe bentuk dilarang. Baca **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Menentukan apakah mengubah ukuran bentuk ini dilarang. Baca **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Menentukan apakah perubahan nilai penyesuaian dilarang. Tulis **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Menentukan apakah perubahan kepala panah dilarang. Tulis **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Menentukan apakah bentuk harus mempertahankan rasio aspek saat diubah ukuran. Tulis **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Menentukan apakah penambahan bentuk ini ke grup dilarang. Tulis **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Menentukan apakah memindahkan bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Menentukan apakah perubahan sudut rotasi bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Menentukan apakah pemilihan bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Menentukan apakah perubahan tipe bentuk dilarang. Tulis **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Menentukan apakah mengubah ukuran bentuk ini dilarang. Tulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Mengatur argumen template ke-n menjadi pointer lemah (bukan berbagi). Memungkinkan perpindahan pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Menambah penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Menambah penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IBaseShapeLock](../ibaseshapelock/)
* Ruang nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)