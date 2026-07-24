---
title: IPictureFillFormat
second_title: C++ için Aspose.Slides API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 3225
url: /tr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat sınıfı

Bir resim doldurma stilini temsil eder.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Görüntüyü şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Doldurma [Picture](../picture/) öğesinin kırpılmış alanlarını sil. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilindeki kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# stilindeki kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Resmin gerçek yüksekliğinin, resmin alt kısmından kırpılan yüzde miktarını döndürür. Okunur **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Resmin gerçek genişliğinin, resmin sol kısmından kırpılan yüzde miktarını döndürür. Okunur **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Resmin gerçek genişliğinin, resmin sağ kısmından kırpılan yüzde miktarını döndürür. Okunur **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Resmin gerçek yüksekliğinin, resmin üst kısmından kırpılan yüzde miktarını döndürür. Okunur **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Resmi doldurmak için kullanılan dpi değerini döndürür. Okunur **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Resmi döndürür. Yalnızca okunur [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Resim doldurma modunu döndürür. Okunur [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Şeklin sınırlayıcı kutusunun alt kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Okunur **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Şeklin sınırlayıcı kutusunun sol kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Okunur **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Okunur **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Şeklin sınırlayıcı kutusunun üst kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Okunur **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl yineleneceğini kontrol eder. Okunur [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Doku döşemesini yatay, dikey veya her iki eksen etrafında çevirir. Okunur [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Doku kaynağının şeklin orijininin yatay kaymasını puan cinsinden döndürür. Pozitif değer dokuyu sağa, negatif değer sola hareket ettirir. Okunur **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Doku kaynağının şeklin orijininin dikey kaymasını puan cinsinden döndürür. Pozitif değer dokuyu aşağı, negatif değer yukarı hareket ettirir. Okunur **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Doku doldurması için yatay ölçeği yüzde olarak döndürür. Okunur **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Doku doldurması için dikey ölçeği yüzde olarak döndürür. Okunur **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Resmin gerçek yüksekliğinin, resmin alt kısmından kırpılan yüzde miktarını ayarlar. Yaz **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Resmin gerçek genişliğinin, resmin sol kısmından kırpılan yüzde miktarını ayarlar. Yaz **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Resmin gerçek genişliğinin, resmin sağ kısmından kırpılan yüzde miktarını ayarlar. Yaz **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Resmin gerçek yüksekliğinin, resmin üst kısmından kırpılan yüzde miktarını ayarlar. Yaz **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Resmi doldurmak için kullanılan dpi değerini ayarlar. Yaz **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Resim doldurma modunu ayarlar. Yaz [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Şeklin sınırlayıcı kutusunun alt kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin alt kenarını ayarlar. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Yaz **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Şeklin sınırlayıcı kutusunun sol kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin sol kenarını ayarlar. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Yaz **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin sağ kenarını ayarlar. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Yaz **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Şeklin sınırlayıcı kutusunun üst kenarından yüzde öteleme ile tanımlanan doldurma dikdörtgeninin üst kenarını ayarlar. Pozitif yüzde bir iç boşluk, negatif yüzde bir dış boşluk belirtir. Yaz **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Doku şekil içinde nasıl hizalanacağını ayarlar. Bu ayar, doku deseninin başlangıç noktasını ve şekil boyunca nasıl yineleneceğini kontrol eder. Yaz [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Doku döşemesini yatay, dikey veya her iki eksen etrafında çevirir. Yaz [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Doku kaynağının şeklin orijininin yatay kaymasını puan cinsinden ayarlar. Pozitif değer dokuyu sağa, negatif değer sola hareket ettirir. Yaz **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Doku kaynağının şeklin orijininin dikey kaymasını puan cinsinden ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı hareket ettirir. Yaz **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Doku doldurma için yatay ölçeği yüzde olarak ayarlar. Yaz **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Doku doldurma için dikey ölçeği yüzde olarak ayarlar. Yaz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki göstergeleri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IFillParamSource](../ifillparamsource/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)