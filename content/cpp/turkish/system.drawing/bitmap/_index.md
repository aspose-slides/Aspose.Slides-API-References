---
title: Bitmap
second_title: Aspose.Slides for C++ API Referansı
description: "GDI+ bitmap görüntüsünü temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığında (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 1
url: /tr/system.drawing/bitmap/
---
## Bitmap class

GDI+ bitmap görüntüsünü temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığında (stack) veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara parametre olarak geçirin.

```cpp
class Bitmap : public System::Drawing::Image
```

## Yöntemler

| Method | Description |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Piksel işleme modunu etkinleştirir. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Belirtilen mevcut görüntüden yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Belirtilen akıştan yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Belirtilen dosyadan yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Belirtilen dosyadan yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Belirtilen genişlik, yükseklik, piksel formatı ve piksel verileriyle bir bitmap görüntüsü temsil eden yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Belirtilen mevcut görüntüden, belirtilen boyuta ölçeklendirilmiş yeni bir [Bitmap](./) nesnesi oluşturur. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Belirtilen mevcut görüntüden, genişlik ve yükseklik belirtilen değerlere ölçeklendirilmiş yeni bir [Bitmap](./) nesnesi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Geçerli nesnenin bir kopyasını oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Geçerli nesne tarafından temsil edilen bitmap görüntüsünün bir bölgesinin kopyasını temsil eden bir [Bitmap](./) nesnesi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Geçerli nesne tarafından temsil edilen bitmap görüntüsünün bir bölgesinin kopyasını temsil eden bir [Bitmap](./) nesnesi oluşturur. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | SHA1 karma değerini hesaplar. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Belirtilen bitmap görüntüsünün piksel formatı Format32bppArgb olarak değiştirilmiş bir kopyasını oluşturur. |
| void [Dispose](../image/dispose/)() override | Geçerli nesne tarafından edinilen tüm kaynakları serbest bırakır. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Piksel işleme modunu devre dışı bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Belirtilen dosyadan bir [Image](../image/) nesnesi oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Belirtilen GDI bitmap'inden bir [Bitmap](./) nesnesi oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Belirtilen akıştan bir [Image](../image/) nesnesi oluşturur. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Görüntünün özniteliklerini temsil eden ImageFlags enum değerlerinin bit düzeyinde birleşimini döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Geçerli nesne tarafından temsil edilen görüntünün çerçeve boyutlarını temsil eden GUID dizisini döndürür. |
| int [get_Height](./get_height/)() const override | Görüntünün yüksekliğini piksel cinsinden döndürür. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Geçerli nesne tarafından temsil edilen görüntünün yatay çözünürlüğünü inç başına piksel olarak döndürür. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Geçerli nesne tarafından temsil edilen görüntü tarafından kullanılan renk paletini döndürür. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Geçerli nesne tarafından temsil edilen görüntünün piksel formatını döndürür. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Bu görüntüde saklanan özellik öğelerinin kimliklerini alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Bu görüntüde saklanan tüm özellik öğelerini (meta veri parçalarını) alır. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Geçerli nesne tarafından temsil edilen görüntünün dosya formatını döndürür. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Görüntünün genişlik ve yüksekliğini piksel cinsinden temsil eden bir [Size](../size/) nesnesi döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Görüntü hakkında ek veri sağlayan bir nesne alır. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Geçerli nesne tarafından temsil edilen görüntünün dikey çözünürlüğünü inç başına piksel olarak döndürür. |
| int [get_Width](./get_width/)() const override | Görüntünün genişliğini piksel cinsinden döndürür. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Belirtilen ölçüm birimlerinde görüntünün sınırlarını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Belirtilen çerçeve boyutunun çerçeve sayısını döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karmalaşmasını etkinleştirir. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Geçerli nesne tarafından temsil edilen bitmap'ten bir GDI bitmap nesnesi oluşturur. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Belirtilen pikselin rengini döndürür. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Belirtilen piksel formatında renk derinliğini temsil etmek için kullanılan bit sayısını döndürür. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Alttaki SkBitmap nesnesine ham bir işaretçi döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Bu [System::Drawing::Image](../image/) nesnesi için bir küçük resim alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Belirtilen piksel formatının alfa bilgisi içerip içermediğini belirler. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Orijinal formatın çoklu görüntü olup olmadığını döndürür. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Bir [Bitmap](./)'yi sistem belleğine kilitler. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Bir [Bitmap](./)'yi sistem belleğine kilitler. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Belirtilen renge sahip tüm piksellerin rengini transparan yapar. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel türlerin klonlanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını ilkleştirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi ilkleştirir ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi ilkleştirir ve alt sınıfların kopya oluşturmalarını sağlar. |
| void [PremultipleColors](./premultiplecolors/)() | Geçerli nesne tarafından temsil edilen görüntünün piksellerinin renklerini önceden çarpar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Görüntüyü 90 derecelik katlara döndürür ve çevirir. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya PNG formatında kaydeder. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya belirtilen formatta kaydeder. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Geçerli nesne tarafından temsil edilen görüntüyü belirtilen akışa belirtilen formatta kaydeder. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Geçerli nesne tarafından temsil edilen görüntüyü belirtilen dosyaya, belirtilen kodlayıcı ve kodlayıcı parametrelerini kullanarak kaydeder. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Geçerli nesne tarafından temsil edilen görüntüyü belirtilen akışa, belirtilen kodlayıcı ve kodlayıcı parametrelerini kullanarak kaydeder. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) yöntemine önceki bir çağrıda belirtilen dosya ya da akışa bir çerçeve ekler. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | [Save()](../image/save/) yöntemine önceki bir çağrıda belirtilen dosya ya da akışa bir çerçeve ekler. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Belirtilen çerçeveyi seçer. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Geçerli nesne tarafından temsil edilen görüntünün kullandığı renk paletini ayarlar. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Görüntü hakkında ek veri sağlayan bir nesne ayarlar. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Geçerli nesne tarafından temsil edilen bitmap görüntüsünde belirtilen pikselin rengini ayarlar. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Görüntünün çözünürlüğünü ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Belirtilen bitmap'i sistem belleğinden kilidi açar. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Image](../image/)
* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)