---
title: Reflection
second_title: Aspose.Slides için C++ API Referansı
description: Bir yansıma etkisini temsil eder.
type: docs
weight: 1067
url: /tr/aspose.slides.effects/reflection/
---
## Reflection sınıfı

Bir [Reflection](./) etkisini temsil eder.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen [Reflection](./)'nin mevcut [Reflection](./) ile eşit olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmadığı C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği, IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmadığı C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) yarıçapı. Okunur **double**. |
| **float** [get_Direction](./get_direction/)() override | Yansımanın yönü. Okunur **float**. |
| **double** [get_Distance](./get_distance/)() override | Yansıma mesafesi. Okunur **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Son alfa değerinin (yüzde) alfa gradyan rampa boyunca son konumunu belirtir. Okunur **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Yansımanın son opaklığı. (yüzde). Okunur **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Yansımanın kaydırma yönünü belirtir. (açı). Okunur **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Ebeveyn [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)'yi döndürür. Salt-okunur [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Dikdörtgen hizalaması. Okunur [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. Okunur **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme ters çevirir. (yüzde) Okunur **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme ters çevirir. (yüzde) Okunur **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Yatay kayma açısını belirtir. Okunur **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Dikey kayma açısını belirtir. Okunur **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Başlangıç alfa değerinin (yüzde) alfa gradyan rampa boyunca başlangıç konumunu belirtir. Okunur **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Başlangıç yansıma opaklığı. (yüzde). Okunur **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Sürüm. Salt-okunur **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Uygulanan kalıtımla etkili [Reflection](./) efekt verisini alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Belirli bir tip için hash işlevi olarak hizmet eder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) yarıçapı. **double** yazar. |
| void [set_Direction](./set_direction/)(**float**) override | Yansımanın yönü. **float** yazar. |
| void [set_Distance](./set_distance/)(**double**) override | Yansıma mesafesi. **double** yazar. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Son alfa değerinin (yüzde) alfa gradyan rampa boyunca son konumunu belirtir. **float** yazar. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Yansımanın son opaklığı. (yüzde). **float** yazar. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Yansımanın kaydırma yönünü belirtir. (açı). **float** yazar. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Dikdörtgen hizalaması. [RectangleAlignment](../../aspose.slides/rectanglealignment/) yazar. |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Şekil döndürülürse yansımanın şekille birlikte döndürülüp döndürülmeyeceğini belirtir. **bool** yazar. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme ters çevirir. (yüzde) **double** yazar. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme ters çevirir. (yüzde) **double** yazar. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Yatay kayma açısını belirtir. **double** yazar. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Dikey kayma açısını belirtir. **double** yazar. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Başlangıç alfa değerinin (yüzde) alfa gradyan rampa boyunca başlangıç konumunu belirtir. **float** yazar. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Başlangıç yansıma opaklığı. (yüzde). **float** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını gerçekleştirir. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını gerçekleştirir. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [IReflection](../ireflection/)
* Sınıf [IVisualEffect](../ivisualeffect/)
* Sınıf [IPVIObject](../../aspose.slides/ipviobject/)
* Ad alanı [Aspose::Slides::Effects](../)
* Kütüphane [Aspose.Slides](../../)