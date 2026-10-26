---
title: PictureFillFormat
second_title: Aspose.Slides untuk Referensi API C++
description: Mewakili gaya isian gambar.
type: docs
weight: 4720
url: /id/aspose.slides/picturefillformat/
---
## PictureFillFormat kelas

Mewakili gaya isian gambar.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Hapus area yang dipotong dari isian [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Membandingkan dengan objek yang ditentukan. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Mengembalikan jumlah persen tinggi gambar asli yang dipotong di bagian bawah gambar. Baca **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Mengembalikan jumlah persen lebar gambar asli yang dipotong di sisi kiri gambar. Baca **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Mengembalikan jumlah persen lebar gambar asli yang dipotong di sisi kanan gambar. Baca **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Mengembalikan jumlah persen tinggi gambar asli yang dipotong di bagian atas gambar. Baca **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Mengembalikan dpi yang digunakan untuk mengisi gambar. Baca **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Mengembalikan objek Parent_Immediate. Hanya-baca [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Mengembalikan [IPresentationComponent](../ipresentationcomponent/) induk. Hanya-baca [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Mengembalikan gambar. Hanya-baca [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Mengembalikan mode isian gambar. Baca [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Mengembalikan tepi bawah persegi panjang isian yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Baca **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Mengembalikan tepi kiri persegi panjang isian yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Baca **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Mengembalikan tepi kanan persegi panjang isian yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Baca **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Mengembalikan tepi atas persegi panjang isian yang ditentukan oleh offset persentase dari tepi atas kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Baca **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Mengembalikan cara tekstur diselaraskan dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana ia diulang di seluruh bentuk. Baca [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Membalik ubin tekstur secara horizontal, vertikal, atau pada kedua sumbu. Baca [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Mengembalikan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Baca **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Mengembalikan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sementara nilai negatif memindahkannya ke atas. Baca **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Mengembalikan skala vertikal untuk isian tekstur sebagai persentase. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Mengembalikan kode hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analogi panggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analogi operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Memungkinkan cloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan memungkinkan pembuatan salinan subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Menetapkan jumlah persen tinggi gambar asli yang dipotong di bagian bawah gambar. Tulis **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Menetapkan jumlah persen lebar gambar asli yang dipotong di sisi kiri gambar. Tulis **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Menetapkan jumlah persen lebar gambar asli yang dipotong di sisi kanan gambar. Tulis **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Menetapkan jumlah persen tinggi gambar asli yang dipotong di bagian atas gambar. Tulis **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Menetapkan dpi yang digunakan untuk mengisi gambar. Tulis **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Menetapkan mode isian gambar. Tulis [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Menetapkan tepi bawah persegi panjang isian yang ditentukan oleh offset persentase dari tepi bawah kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Tulis **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Menetapkan tepi kiri persegi panjang isian yang ditentukan oleh offset persentase dari tepi kiri kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Tulis **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Menetapkan tepi kanan persegi panjang isian yang ditentukan oleh offset persentase dari tepi kanan kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Tulis **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Menetapkan tepi atas persegi panjang isian yang ditentukan oleh offset persentase dari tepi atas kotak pembatas bentuk. Persentase positif menunjukkan penyusutan, sementara persentase negatif menunjukkan penonjolan. Tulis **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Menetapkan cara tekstur diselaraskan dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana ia diulang di seluruh bentuk. Tulis [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Membalik ubin tekstur secara horizontal, vertikal, atau pada kedua sumbu. Tulis [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Menetapkan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Tulis **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Menetapkan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sementara nilai negatif memindahkannya ke atas. Tulis **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Menetapkan skala horizontal untuk isian tekstur sebagai persentase. Tulis **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Menetapkan skala vertikal untuk isian tekstur sebagai persentase. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer menjadi mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi metode C# [Object.ToString()](../../system/object/tostring/). Memungkinkan mengubah objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pembukaan kunci pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi weak. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi weak. Tidak seharusnya dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [PVIObject](../pviobject/)
* Kelas [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)