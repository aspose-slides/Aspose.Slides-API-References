---
title: AutoShapeLock
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan operasi mana yang dinonaktifkan pada AutoshapeEx induk.
type: docs
weight: 79
url: /id/aspose.slides/autoshapelock/
---
## AutoShapeLock kelas

Menentukan operasi mana yang dinonaktifkan pada AutoshapeEx induk.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Menentukan apakah perubahan nilai penyesuaian dilarang. Baca **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Menentukan apakah perubahan kepala panah dilarang. Baca **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Menentukan apakah suatu bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Baca **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Baca **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Menentukan apakah penambahan bentuk ini ke grup dilarang. Baca **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Mengembalikan true jika semua flag penguncian dinonaktifkan. Baca-saja **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Menentukan apakah memindahkan bentuk ini dilarang. Baca **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Menentukan apakah perubahan sudut rotasi bentuk ini dilarang. Baca **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Menentukan apakah pemilihan bentuk ini dilarang. Baca **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Menentukan apakah perubahan tipe bentuk dilarang. Baca **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Menentukan apakah mengubah ukuran bentuk ini dilarang. Baca **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Menentukan apakah penyuntingan teks dilarang. Baca **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogi metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subkelas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Menentukan apakah perubahan nilai penyesuaian dilarang. Tulis **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Menentukan apakah perubahan kepala panah dilarang. Tulis **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Menentukan apakah suatu bentuk harus mempertahankan rasio aspek saat mengubah ukuran. Tulis **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Menentukan apakah perubahan langsung kontur bentuk ini dilarang. Tulis **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Menentukan apakah penambahan bentuk ini ke grup dilarang. Tulis **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Menentukan apakah memindahkan bentuk ini dilarang. Tulis **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Menentukan apakah perubahan sudut rotasi bentuk ini dilarang. Tulis **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Menentukan apakah pemilihan bentuk ini dilarang. Tulis **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Menentukan apakah perubahan tipe bentuk dilarang. Tulis **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Menentukan apakah mengubah ukuran bentuk ini dilarang. Tulis **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Menentukan apakah penyuntingan teks dilarang. Tulis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen templat ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil secara langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointers atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [BaseShapeLock](../baseshapelock/)
* Kelas [IAutoShapeLock](../iautoshapelock/)
* Ruang nama [Aspose::Slides](../)
* Library [Aspose.Slides](../../)