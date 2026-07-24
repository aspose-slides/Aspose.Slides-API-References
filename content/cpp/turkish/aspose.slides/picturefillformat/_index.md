---
title: PictureFillFormat
second_title: Aspose.Slides for C++ API Referansı
description: Bir resim doldurma stilini temsil eder.
type: docs
weight: 4720
url: /tr/aspose.slides/picturefillformat/
---
## PictureFillFormat sınıfı

Bir resim doldurma stilini temsil eder.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Görüntüyü, şekil boyutuna ve belirtilen çözünürlüğe göre boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Doldurma [Picture](../picture/)'nin kırpılmış alanlarını sil. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, C# stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Resmin alt kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını döndürür. **float** okunur. |
| **float** [get_CropLeft](./get_cropleft/)() override | Resmin sol kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını döndürür. **float** okunur. |
| **float** [get_CropRight](./get_cropright/)() override | Resmin sağ kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını döndürür. **float** okunur. |
| **float** [get_CropTop](./get_croptop/)() override | Resmin üst kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını döndürür. **float** okunur. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Bir resmi doldurmak için kullanılan dpi değerini döndürür. **int32_t** okunur. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Salt okunur [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/)'yi döndürür. Salt okunur [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Resmi döndürür. Salt okunur [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Resim doldurma kipini döndürür. [Slides::PictureFillMode](../picturefillmode/) okunur. |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını döndürür. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** okunur. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını döndürür. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** okunur. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını döndürür. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** okunur. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını döndürür. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** okunur. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Doku şekil içinde nasıl hizalandığını döndürür. Bu ayar doku deseninin başlangıç noktasını ve şekil üzerindeki tekrarını kontrol eder. [RectangleAlignment](../rectanglealignment/) okunur. |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Doku karoselini yatay, dikey veya her iki eksen etrafında çevirir. [Slides::TileFlip](../tileflip/) okunur. |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Doku'nun şeklin orijinalinden yatay offsetini puan cinsinden döndürür. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. **float** okunur. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Doku'nun şeklin orijinalinden dikey offsetini puan cinsinden döndürür. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. **float** okunur. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Doku doldurması için yatay ölçeği yüzde olarak döndürür. **float** okunur. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Doku doldurması için dikey ölçeği yüzde olarak döndürür. **float** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel bir uygulamasıdır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel bir uygulamasıdır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Resmin alt kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını ayarlar. **float** yazılır. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Resmin sol kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını ayarlar. **float** yazılır. |
| void [set_CropRight](./set_cropright/)(**float**) override | Resmin sağ kısmından kırpılan gerçek görüntü genişliğinin yüzde miktarını ayarlar. **float** yazılır. |
| void [set_CropTop](./set_croptop/)(**float**) override | Resmin üst kısmından kırpılan gerçek görüntü yüksekliğinin yüzde miktarını ayarlar. **float** yazılır. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Bir resmi doldurmak için kullanılan dpi değerini ayarlar. **int32_t** yazılır. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Resim doldurma kipini ayarlar. [Slides::PictureFillMode](../picturefillmode/) yazılır. |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Şeklin sınırlayıcı kutusunun alt kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin alt kenarını ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** yazılır. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Şeklin sınırlayıcı kutusunun sol kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sol kenarını ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** yazılır. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Şeklin sınırlayıcı kutusunun sağ kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin sağ kenarını ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** yazılır. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Şeklin sınırlayıcı kutusunun üst kenarından yüzde offset ile tanımlanan doldurma dikdörtgeninin üst kenarını ayarlar. Pozitif yüzde içeri girişi, negatif yüzde dışarı çıkışı belirtir. **float** yazılır. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Doku'nun şekil içinde nasıl hizalanacağını ayarlar. Bu ayar doku deseninin başlangıç noktasını ve şekildeki tekrarını kontrol eder. [RectangleAlignment](../rectanglealignment/) yazılır. |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Doku karoselini yatay, dikey veya her iki eksen etrafında çevirir. [Slides::TileFlip](../tileflip/) yazılır. |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Doku'nun şeklin orijinalinden yatay offsetini puan cinsinden ayarlar. Pozitif değer dokuyu sağa, negatif değer sola kaydırır. **float** yazılır. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Doku'nun şeklin orijinalinden dikey offsetini puan cinsinden ayarlar. Pozitif değer dokuyu aşağı, negatif değer yukarı kaydırır. **float** yazılır. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Doku doldurma için yatay ölçeği yüzde olarak ayarlar. **float** yazılır. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Doku doldurma için dikey ölçeği yüzde olarak ayarlar. **float** yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [PVIObject](../pviobject/)
* Sınıf [IPictureFillFormat](../ipicturefillformat/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)