---
title: Bitmap
second_title: Aspose.Slides untuk Referensi API C++
description: "Mewakili gambar bitmap GDI+. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen."
type: docs
weight: 1
url: /id/system.drawing/bitmap/
---
## Bitmap kelas

Mewakili gambar bitmap GDI+. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan waktu berjalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen.

```cpp
class Bitmap : public System::Drawing::Image
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Mengaktifkan mode pemrosesan piksel. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Membuat objek [Bitmap](./) baru dari gambar yang ada yang ditentukan. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Membuat objek [Bitmap](./) baru dari stream yang ditentukan. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Membuat objek [Bitmap](./) baru dari file yang ditentukan. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Membuat objek [Bitmap](./) baru dari file yang ditentukan. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Membuat objek [Bitmap](./) baru yang mewakili gambar bitmap dengan lebar, tinggi, format piksel, dan data piksel yang ditentukan. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Membuat objek [Bitmap](./) baru dari gambar yang ada yang ditentukan, diubah ukurannya ke ukuran yang ditentukan. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Membuat objek [Bitmap](./) baru dari gambar yang ada yang ditentukan dengan lebar dan tinggi diubah ke nilai yang ditentukan. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Membuat salinan objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Membuat objek [Bitmap](./) yang mewakili salinan wilayah gambar bitmap yang diwakili oleh objek saat ini. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Membuat objek [Bitmap](./) yang mewakili salinan wilayah gambar bitmap yang diwakili oleh objek saat ini. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Menghitung nilai hash SHA1. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Membuat salinan gambar bitmap yang ditentukan dengan format piksel diubah menjadi Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Melepaskan semua sumber daya yang dimiliki oleh objek saat ini. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Menonaktifkan mode pemrosesan piksel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang gaya C# dimana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk keperluan internal. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Membuat objek [Image](../image/) dari file yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Membuat objek [Bitmap](./) dari GDI bitmap yang ditentukan. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Membuat objek [Image](../image/) dari stream yang ditentukan. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Mengembalikan kombinasi bitwise dari nilai enum ImageFlags yang mewakili atribut gambar. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Mengembalikan array GUID yang mewakili dimensi frame dalam gambar yang diwakili oleh objek saat ini. |
| int [get_Height](./get_height/)() const override | Mengembalikan tinggi gambar dalam piksel. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Mengembalikan resolusi horizontal gambar yang diwakili oleh objek saat ini dalam piksel per inci. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Mengembalikan palet warna yang digunakan oleh gambar yang diwakili oleh objek saat ini. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Mengembalikan format piksel gambar yang diwakili oleh objek saat ini. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Mendapatkan ID dari item properti yang disimpan dalam gambar ini. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Mendapatkan semua item properti (potongan metadata) yang disimpan dalam gambar ini. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Mengembalikan format file gambar yang diwakili oleh objek saat ini. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Mengembalikan objek [Size](../size/) yang mewakili lebar dan tinggi gambar dalam piksel. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Mendapatkan objek yang menyediakan data tambahan tentang gambar. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Mengembalikan resolusi vertikal gambar yang diwakili oleh objek saat ini dalam piksel per inci. |
| int [get_Width](./get_width/)() const override | Mengembalikan lebar gambar dalam piksel. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Mengembalikan batas gambar dalam satuan ukuran yang ditentukan. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mendapatkan struktur data penghitung referensi yang terkait dengan objek. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Mengembalikan jumlah frame dari dimensi frame yang ditentukan. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog dari metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek khusus. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Membuat objek bitmap GDI dari bitmap yang diwakili oleh objek saat ini. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Mengembalikan warna piksel yang ditentukan. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Mengembalikan jumlah bit yang digunakan untuk merepresentasikan kedalaman warna dalam format piksel yang ditentukan. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Mengembalikan pointer mentah ke objek SkBitmap yang mendasarinya. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Mendapatkan thumbnail untuk objek [System::Drawing::Image](../image/) ini. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengetahui tipe sebenarnya dari objek. Analog dari pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek mewakili instance dari tipe yang dijelaskan oleh targetType. Analog dari operator C# 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Menentukan apakah format piksel yang ditentukan mengandung informasi alfa. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Mengembalikan apakah format asli merupakan multi-image. |
| void [Lock](../../system/object/lock/)() | Menerapkan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Mengunci [Bitmap](./) ke dalam memori sistem. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Mengunci [Bitmap](./) ke dalam memori sistem. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Mengubah warna semua piksel dengan warna yang ditentukan menjadi transparan. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog dari metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe khusus. |
| [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor penyalinan. Tidak menyalin apa pun, sebenarnya hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya hanya menginisialisasi objek baru dan memungkinkan penyalinan konstruktor subclass. |
| void [PremultipleColors](./premultiplecolors/)() | Melakukan premultiplikasi warna piksel gambar yang diwakili oleh objek saat ini. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi hitungan referensi bersama sebesar nilai yang ditentukan. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Memutar gambar ke kelipatan 90 derajat dan membaliknya. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan dalam format PNG. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan dalam format yang ditentukan. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Menyimpan gambar yang diwakili oleh objek saat ini ke stream yang ditentukan dalam format yang ditentukan. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Menyimpan gambar yang diwakili oleh objek saat ini ke file yang ditentukan menggunakan encoder dan parameter encoder yang ditentukan. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Menyimpan gambar yang diwakili oleh objek saat ini ke stream yang ditentukan menggunakan encoder dan parameter encoder yang ditentukan. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Menambahkan frame ke file atau stream yang ditentukan dalam pemanggilan sebelumnya ke metode [Save()](../image/save/). |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Menambahkan frame ke file atau stream yang ditentukan dalam pemanggilan sebelumnya ke metode [Save()](../image/save/). |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Memilih frame yang ditentukan. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Menetapkan palet warna yang digunakan oleh gambar yang diwakili oleh objek saat ini. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Menetapkan objek yang menyediakan data tambahan tentang gambar. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Menetapkan warna piksel yang ditentukan dalam gambar bitmap yang diwakili oleh objek saat ini. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Menetapkan resolusi gambar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi weak pointer (bukan shared). Memungkinkan mengubah pointer dalam kontainer ke mode weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mendapatkan nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan hitungan referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog dari metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek khusus menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Menerapkan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Menerapkan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Membuka kunci bitmap yang ditentukan dari memori sistem. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi hitungan referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |

## Lihat Juga

* Kelas [Image](../image/)
* Ruang Nama [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)