---
title: IPictureFrameLock
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan operasi mana yang dinonaktifkan pada PictureFrameEx induk.
type: docs
weight: 3264
url: /id/aspose.slides/ipictureframelock/
---
## IPictureFrameLock kelas


Menentukan operasi mana yang dinonaktifkan pada PictureFrameEx induk.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dalam gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Menentukan apakah mengubah nilai penyesuaian dilarang. Baca **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Menentukan apakah mengubah kepala panah dilarang. Baca **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Menentukan apakah sebuah bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Baca **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Menentukan apakah memotong gambar dilarang. Baca **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Menentukan apakah mengubah kontur bentuk ini secara langsung dilarang. Baca **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Menentukan apakah menambahkan bentuk ini ke grup dilarang. Baca **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Mengembalikan true jika semua flag kunci dinonaktifkan. Hanya-baca **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Menentukan apakah memindahkan bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Menentukan apakah mengubah sudut rotasi bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Menentukan apakah memilih bentuk ini dilarang. Baca **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Menentukan apakah mengubah tipe bentuk dilarang. Baca **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Menentukan apakah mengubah ukuran bentuk ini dilarang. Baca **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe sesungguhnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan pernyataan lock() C# untuk mengunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Sebenarnya tidak menyalin apa pun, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Menentukan apakah mengubah nilai penyesuaian dilarang. Tulis **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Menentukan apakah mengubah kepala panah dilarang. Tulis **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Menentukan apakah sebuah bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Tulis **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Menentukan apakah memotong gambar dilarang. Tulis **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Menentukan apakah mengubah kontur bentuk ini secara langsung dilarang. Tulis **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Menentukan apakah menambahkan bentuk ini ke grup dilarang. Tulis **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Menentukan apakah memindahkan bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Menentukan apakah mengubah sudut rotasi bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Menentukan apakah memilih bentuk ini dilarang. Tulis **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Menentukan apakah mengubah tipe bentuk dilarang. Tulis **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Menentukan apakah mengubah ukuran bentuk ini dilarang. Tulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pernyataan lock() C# untuk membuka kunci. Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IBaseShapeLock](../ibaseshapelock/)
* Ruang Nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)