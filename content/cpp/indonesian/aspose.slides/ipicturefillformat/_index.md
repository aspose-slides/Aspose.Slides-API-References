---
title: IPictureFillFormat
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili gaya isian gambar.
type: docs
weight: 3225
url: /id/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat kelas

Mewakili gaya isian gambar.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Mengompresi gambar dengan mengurangi ukurannya berdasarkan ukuran bentuk dan resolusi yang ditentukan. Secara opsional, juga menghapus area yang dipotong. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Menghapus area yang dipotong dari isian [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Mengembalikan persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. Baca **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Mengembalikan persentase lebar gambar asli yang dipotong dari sisi kiri gambar. Baca **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Mengembalikan persentase lebar gambar asli yang dipotong dari sisi kanan gambar. Baca **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Mengembalikan persentase tinggi gambar asli yang dipotong dari bagian atas gambar. Baca **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Mengembalikan dpi yang digunakan untuk mengisi gambar. Baca **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Mengembalikan gambar. Baca-saja [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Mengembalikan mode isian gambar. Baca [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Mengembalikan tepi bawah persegi panjang isian yang didefinisikan oleh offset persentase dari tepi bawah kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Baca **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Mengembalikan tepi kiri persegi panjang isian yang didefinisikan oleh offset persentase dari tepi kiri kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Baca **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Mengembalikan tepi kanan persegi panjang isian yang didefinisikan oleh offset persentase dari tepi kanan kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Baca **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Mengembalikan tepi atas persegi panjang isian yang didefinisikan oleh offset persentase dari tepi atas kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Baca **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Mengembalikan cara tekstur disejajarkan dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana ia diulang di seluruh bentuk. Baca [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Baca [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Mengembalikan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Baca **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Mengembalikan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sementara nilai negatif memindahkannya ke atas. Baca **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Mengembalikan skala horizontal untuk isian tekstur sebagai persentase. Baca **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Mengembalikan skala vertikal untuk isian tekstur sebagai persentase. Baca **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mendapatkan tipe aktual objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili sebuah instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya, hanya menginisialisasi objek baru dan mengaktifkan pembuatan salinan pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Menetapkan persentase tinggi gambar asli yang dipotong dari bagian bawah gambar. Tulis **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Menetapkan persentase lebar gambar asli yang dipotong dari sisi kiri gambar. Tulis **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Menetapkan persentase lebar gambar asli yang dipotong dari sisi kanan gambar. Tulis **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Menetapkan persentase tinggi gambar asli yang dipotong dari bagian atas gambar. Tulis **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Menetapkan dpi yang digunakan untuk mengisi gambar. Tulis **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Menetapkan mode isian gambar. Tulis [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Menetapkan tepi bawah persegi panjang isian yang didefinisikan oleh offset persentase dari tepi bawah kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Tulis **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Menetapkan tepi kiri persegi panjang isian yang didefinisikan oleh offset persentase dari tepi kiri kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Tulis **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Menetapkan tepi kanan persegi panjang isian yang didefinisikan oleh offset persentase dari tepi kanan kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Tulis **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Menetapkan tepi atas persegi panjang isian yang didefinisikan oleh offset persentase dari tepi atas kotak pembatas bentuk. Persentase positif menunjukkan inset, sementara persentase negatif menunjukkan outset. Tulis **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Menetapkan cara tekstur disejajarkan dalam bentuk. Pengaturan ini mengontrol titik awal pola tekstur dan bagaimana ia diulang di seluruh bentuk. Tulis [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Membalik ubin tekstur di sekitar sumbu horizontal, vertikal, atau keduanya. Tulis [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Menetapkan offset horizontal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke kanan, sementara nilai negatif memindahkannya ke kiri. Tulis **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Menetapkan offset vertikal tekstur dari asal bentuk dalam poin. Nilai positif memindahkan tekstur ke bawah, sementara nilai negatif memindahkannya ke atas. Tulis **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Menetapkan skala horizontal untuk isian tekstur sebagai persentase. Tulis **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Menetapkan skala vertikal untuk isian tekstur sebagai persentase. Tulis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus ke string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruksi C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek pengawas [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil secara langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [IFillParamSource](../ifillparamsource/)
* Ruang Nama [Aspose::Slides](../)
* Pustaka [Aspose.Slides](../../)