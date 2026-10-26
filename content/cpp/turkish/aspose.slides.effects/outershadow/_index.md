---
title: OuterShadow
second_title: Aspose.Slides için C++ API Referansı
description: Dış Gölge etkisini temsil eder.
type: docs
weight: 1041
url: /tr/aspose.slides.effects/outershadow/
---
## OuterShadow sınıf

Dış Gölge etkisini temsil eder.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen [OuterShadow](./)'nin mevcut [OuterShadow](./) ile eşit olup olmadığını belirler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) yarıçap, nokta cinsinden. Varsayılan değer – 0 pt. Okunur **double**. |
| **float** [get_Direction](./get_direction/)() override | Gölgenin yönü, derece cinsinden. Varsayılan değer – 0 ° (sol-sağ). Okunur **float**. |
| **double** [get_Distance](./get_distance/)() override | Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer – 0 pt. Okunur **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)'yi döndürür. Salt okunur [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Dikdörtgen hizalaması. Varsayılan değer – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Okunur [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer – true. Okunur **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Orijinal boyutun yüzde cinsinden yatay ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer – %100. Okunur **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Orijinal boyutun yüzde cinsinden dikey ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer – %100. Okunur **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Gölgenin rengi. Varsayılan değer – otomatik siyah (tema bağımlı). Salt okunur [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Yatay çarpıtma açısı, derece cinsinden. Varsayılan değer – 0 °. Okunur **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Dikey çarpıtma açısı, derece cinsinden. Varsayılan değer – 0 °. Okunur **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Sürüm. Salt okunur **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Kalıtım uygulanmış etkili Dış Gölge etkisi verilerini alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Belirli bir tip için karma işlevi olarak hizmet eder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize ve nullptr durumuna özgü özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumuna özgü özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) yarıçap, nokta cinsinden. Varsayılan değer – 0 pt. Yazılır **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Gölgenin yönü, derece cinsinden. Varsayılan değer – 0 ° (sol-sağ). Yazılır **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Gölgenin nesneden uzaklığı, nokta cinsinden. Varsayılan değer – 0 pt. Yazılır **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Dikdörtgen hizalaması. Varsayılan değer – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Yazılır [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Gölgenin şekil ile birlikte döndürülüp döndürülmediğini gösterir. Varsayılan değer – true. Yazılır **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Orijinal boyutun yüzde cinsinden yatay ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer – %100. Yazılır **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Orijinal boyutun yüzde cinsinden dikey ölçek faktörü. Negatif ölçekleme ters çevirme oluşturur. Varsayılan değer – %100. Yazılır **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Yatay çarpıtma açısı, derece cinsinden. Varsayılan değer – 0 °. Yazılır **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Dikey çarpıtma açısı, derece cinsinden. Varsayılan değer – 0 °. Yazılır **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## İlgili

* Sınıf [IOuterShadow](../ioutershadow/)
* Sınıf [IVisualEffect](../ivisualeffect/)
* Sınıf [IPVIObject](../../aspose.slides/ipviobject/)
* İsim Uzayı [Aspose::Slides::Effects](../)
* Kütüphane [Aspose.Slides](../../)