---
title: IOuterShadow
second_title: Aspose.Slides için C++ API Referansı
description: Bir dış gölge etkisini temsil eder.
type: docs
weight: 885
url: /tr/aspose.slides.effects/ioutershadow/
---
## IOuterShadow sınıfı

Bir dış gölge etkisini temsil eder.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) yarıçap, puan cinsinden. Varsayılan değer – 0 pt. Okur **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Gölgenin yönü, derece cinsinden. Varsayılan değer – 0 \u00B0 (soldan sağa). Okur **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Gölgenin nesneden uzaklığı, puan cinsinden. Varsayılan değer – 0 pt. Okur **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Dikdörtgen hizalaması. Varsayılan değer – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Okur [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer – true. Okur **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Orijinal boyutun yüzde cinsinden yatay ölçeklendirme faktörü. Negatif ölçekleme bir çevirme yapar. Varsayılan değer – 100 %. Okur **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Orijinal boyutun yüzde cinsinden dikey ölçeklendirme faktörü. Negatif ölçekleme bir çevirme yapar. Varsayılan değer – 100 %. Okur **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Gölgenin rengi. Varsayılan değer – otomatik siyah (tema bağımlı). Yalnızca okuma [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Yatay eğim açısı, derece cinsinden. Varsayılan değer – 0 \u00B0. Okur **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Dikey eğim açısı, derece cinsinden. Varsayılan değer – 0 \u00B0. Okur **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Kalıtım uygulanmış etkili veriyi alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin karma değerini oluşturmayı sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans bazında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans bazında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler durumu için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) yarıçap, puan cinsinden. Varsayılan değer – 0 pt. Yazar **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Gölgenin yönü, derece cinsinden. Varsayılan değer – 0 \u00B0 (soldan sağa). Yazar **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Gölgenin nesneden uzaklığı, puan cinsinden. Varsayılan değer – 0 pt. Yazar **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Dikdörtgen hizalaması. Varsayılan değer – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Yazar [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Gölgenin şekil ile birlikte dönüp dönmediğini gösterir. Varsayılan değer – true. Yazar **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Orijinal boyutun yüzde cinsinden yatay ölçeklendirme faktörü. Negatif ölçekleme bir çevirme yapar. Varsayılan değer – 100 %. Yazar **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Orijinal boyutun yüzde cinsinden dikey ölçeklendirme faktörü. Negatif ölçekleme bir çevirme yapar. Varsayılan değer – 100 %. Yazar **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Yatay eğim açısı, derece cinsinden. Varsayılan değer – 0 \u00B0. Yazar **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Dikey eğim açısı, derece cinsinden. Varsayılan değer – 0 \u00B0. Yazar **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IImageTransformOperation](../iimagetransformoperation/)
* Sınıf [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* İsim Alanı [Aspose::Slides::Effects](../)
* Kütüphane [Aspose.Slides](../../)