---
title: IReflection
second_title: Aspose.Slides için C++ API Referansı
description: Bir yansıma etkisini temsil eder.
type: docs
weight: 937
url: /tr/aspose.slides.effects/ireflection/
---
## IReflection sınıf

Bir yansıma etkisini temsil eder.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) yarıçap. **double** okur. |
| virtual **float** [get_Direction](./get_direction/)() | Yansıma yönü. **float** okur. |
| virtual **double** [get_Distance](./get_distance/)() | Yansıma mesafesi. **double** okur. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Alfa degrade ramp boyunca son alfa değerinin (yüzde) bitiş konumunu belirtir. **float** okur. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Yansımanın son opaklığı. (yüzde). **float** okur. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Yansımanın kaydırma yönünü belirtir. (açı). **float** okur. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Dikdörtgen hizalaması. [RectangleAlignment](../../aspose.slides/rectanglealignment/) okur. |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Şekil döndürülürse yansımanın da şekille birlikte döndürülüp döndürülmeyeceğini belirtir. **bool** okur. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir ters çevirme oluşturur. (yüzde) **double** okur. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir ters çevirme oluşturur. (yüzde) **double** okur. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Yatay eğim açısını belirtir. **double** okur. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Dikey eğim açısını belirtir. **double** okur. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Alfa degrade ramp boyunca başlangıç alfa değerinin (yüzde) başlangıç konumunu belirtir. **float** okur. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Başlangıç yansıma opaklığı. (yüzde). **float** okur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Kalıtım uygulanmış etkili veriyi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) yarıçap. **double** yazar. |
| virtual void [set_Direction](./set_direction/)(**float**) | Yansıma yönü. **float** yazar. |
| virtual void [set_Distance](./set_distance/)(**double**) | Yansıma mesafesi. **double** yazar. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Alfa degrade ramp boyunca son alfa değerinin (yüzde) bitiş konumunu belirtir. **float** yazar. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Yansımanın son opaklığı. (yüzde). **float** yazar. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Yansımanın kaydırma yönünü belirtir. (açı). **float** yazar. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Dikdörtgen hizalaması. [RectangleAlignment](../../aspose.slides/rectanglealignment/) yazar. |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Şekil döndürülürse yansımanın da şekille birlikte döndürülüp döndürülmeyeceğini belirtir. **bool** yazar. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir ters çevirme oluşturur. (yüzde) **double** yazar. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir ters çevirme oluşturur. (yüzde) **double** yazar. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Yatay eğim açısını belirtir. **double** yazar. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Dikey eğim açısını belirtir. **double** yazar. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Alfa degrade ramp boyunca başlangıç alfa değerinin (yüzde) başlangıç konumunu belirtir. **float** yazar. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Başlangıç yansıma opaklığı. (yüzde). **float** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IImageTransformOperation](../iimagetransformoperation/)
* Sınıf [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Ad alanı [Aspose::Slides::Effects](../)
* Kütüphane [Aspose.Slides](../../)