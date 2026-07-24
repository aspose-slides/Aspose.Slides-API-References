---
title: Image
second_title: Aspose.Slides for C++ API Referansı
description: "System::Drawing::Bitmap ve System::Drawing::Metafile sınıfları için temel işlevsellik sağlayan bir temel sınıftır. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tür bir örneği yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 144
url: /tr/system.drawing/image/
---
## Image sınıfı

Temel işlevsellik sağlayan [System::Drawing::Bitmap](../bitmap/) ve System::Drawing::Metafile sınıfları için bir temel sınıftır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tür bir örneği yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class Image : public virtual System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [Clone](./clone/)() | Mevcut nesnenin bir kopyasını oluşturur. |
| void [Dispose](./dispose/)() override | Mevcut nesne tarafından edinilen tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için kullanılır. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromFile](./fromfile/)(const [String](../../system/string/)\&, **bool**) | Belirtilen dosyadan bir [Image](./) nesnesi oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../bitmap/)\> [FromHbitmap](./fromhbitmap/)(IntPtr) | Belirtilen GDI bitmapinden bir [Bitmap](../bitmap/) nesnesi oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromStream](./fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Belirtilen akıştan bir [Image](./) nesnesi oluşturur. |
| virtual **int32_t** [get_Flags](./get_flags/)() const | Görüntünün özelliklerini temsil eden ImageFlags enum değerlerinin bit düzeyinde birleşimini döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](./get_framedimensionslist/)() const | Mevcut nesne tarafından temsil edilen görüntü içinde çerçevelerin boyutlarını temsil eden GUID'lerin bir dizisini döndürür. |
| virtual int [get_Height](./get_height/)() const | Görüntünün yüksekliğini piksel cinsinden döndürür. |
| **float** [get_HorizontalResolution](./get_horizontalresolution/)() const | Mevcut nesne tarafından temsil edilen görüntünün yatay çözünürlüğünü inç başına piksel olarak döndürür. |
| virtual [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const | Mevcut nesne tarafından temsil edilen görüntüde kullanılan renk paletini döndürür. |
| virtual [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const | Mevcut nesne tarafından temsil edilen görüntünün piksel formatını döndürür. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](./get_propertyidlist/)() const | Bu görüntüde depolanmış özellik öğelerinin kimliklerini alır. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](./get_propertyitems/)() const | Bu görüntüde depolanmış tüm özellik öğelerini (metadata parçalarını) alır. |
| virtual [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const | Mevcut nesne tarafından temsil edilen görüntünün dosya formatını döndürür. |
| [Size](../size/) [get_Size](./get_size/)() const | Görüntünün genişlik ve yüksekliğini piksel cinsinden temsil eden bir [Size](../size/) nesnesi döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](./get_tag/)() const | Görüntü hakkında ek veri sağlayan bir nesneyi alır. |
| **float** [get_VerticalResolution](./get_verticalresolution/)() const | Mevcut nesne tarafından temsil edilen görüntünün dikey çözünürlüğünü inç başına piksel olarak döndürür. |
| virtual int [get_Width](./get_width/)() const | Görüntünün genişliğini piksel cinsinden döndürür. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Belirtilen ölçü birimlerinde görüntü sınırlarını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| int [GetFrameCount](./getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Belirtilen çerçeve boyutundaki çerçeve sayısını döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| static int [GetPixelFormatSize](./getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Belirtilen piksel formatında renk derinliğini temsil etmek için kullanılan bit sayısını döndürür. |
| virtual const SkBitmap * [GetSkBitmap](./getskbitmap/)() const | Altta yatan bir SkBitmap nesnesini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [GetThumbnailImage](./getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](./getthumbnailimageabort/), IntPtr) | Bu [System::Drawing::Image](./) nesnesi için bir küçük resim alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| static **bool** [IsAlphaPixelFormat](./isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Belirtilen piksel formatının alfa bilgisi içerip içermediğini belirler. |
| virtual **bool** [IsMultiImage](./ismultiimage/)() const | Orijinal formatın çoklu görüntü olup olmadığını döndürür. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) | Görüntüyü 90 derece katları kadar döndürür ve çevirir. |
| void [Save](./save/)(const [String](../../system/string/)\&) | Mevcut nesne tarafından temsil edilen görüntüyü belirtilen dosyaya PNG formatında kaydeder. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Mevcut nesne tarafından temsil edilen görüntüyü belirtilen dosyaya belirtilen formatta kaydeder. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Mevcut nesne tarafından temsil edilen görüntüyü belirtilen akışa belirtilen formatta kaydeder. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Mevcut nesne tarafından temsil edilen görüntüyü belirtilen dosyaya belirtilen kodlayıcı ve kodlayıcı parametreleriyle kaydeder. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Mevcut nesne tarafından temsil edilen görüntüyü belirtilen akışa belirtilen kodlayıcı ve kodlayıcı parametreleriyle kaydeder. |
| void [SaveAdd](./saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Önceki [Save()](./save/) yöntemi çağrısında belirtilen dosyaya veya akışa bir çerçeve ekler. |
| void [SaveAdd](./saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](./)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Önceki [Save()](./save/) yöntemi çağrısında belirtilen dosyaya veya akışa bir çerçeve ekler. |
| int [SelectActiveFrame](./selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Belirtilen çerçeveyi seçer. |
| virtual void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) | Mevcut nesne tarafından temsil edilen görüntüde kullanılan renk paletini ayarlar. |
| virtual void [set_Tag](./set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Görüntü hakkında ek veri sağlayan bir nesneyi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilitleme açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımlamaları

| Tip Tanımı | Açıklama |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | GetThumbnailImage yürütmesini iptal etmek için bir geri çağırma. |

## Ayrıca

* Sınıf [IDisposable](../../system/idisposable/)
* Ad Alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)