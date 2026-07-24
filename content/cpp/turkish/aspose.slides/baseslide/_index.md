---
title: BaseSlide
second_title: Aspose.Slides for C++ API Referansı
description: Tüm slayt türleri için ortak verileri temsil eder.
type: docs
weight: 170
url: /tr/aspose.slides/baseslide/
---
## BaseSlide sınıfı


Tüm slayt türleri için ortak verileri temsil eder.

```cpp
class BaseSlide : public virtual Aspose::Slides::IBaseSlide,
                  public Aspose::Slides::IDOMObject,
                  public Aspose::Slides::IStyleColorOwner
```

## Metotlar

| Metod | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Bu slayt için etkili bir temayı döndürür. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | İki [IBaseSlide](../ibaseslide/) örneğinin eşit olup olmadığını belirler. Döndürülen değer, slaytın yapısına ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerleri ve Date [Placeholder](../placeholder/)'deki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stiliyle karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmadığına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değerle, NaN dahil, eşit olmadığına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) override | Belirtilen alternatif metne sahip şeklin ilk görünümünü bulur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() override | Slaytın arka planını döndürür. Salt okunur [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) override | Belirtilen dizindeki ActiveX denetimini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() override | Bir slayttaki ActiveX denetimleri koleksiyonunu döndürür. Salt okunur [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Slaytın özel verilerini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | İçerilen köprü bağlantılarına kolay erişim sağlar. Salt okunur [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Bir slaytın adını döndürür. Okunur [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | [IPresentation](../ipresentation/) arayüzünü döndürür. Salt okunur [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | Belirtilen dizindeki şekli döndürür. Salt okunur [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | Bir slaytın şekillerini döndürür. Salt okunur [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman **false** döndürür. Okunur **bool**. |
| **uint32_t** [get_SlideId](./get_slideid/)() override | Bir slaytin kimliğini döndürür. Salt okunur **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() override | Belirtilen slaytın bir slayt gösterisi sırasında nasıl ilerleyeceği hakkında bilgi içeren Transition nesnesini döndürür. Salt okunur [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() override | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin karma değerini oluşturmayı etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Tüm paragraf ve uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Tüm paragraf ve uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Bir slaytın adını ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt için bu özellik her zaman **false** döndürür. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBaseSlide](../ibaseslide/)
* Sınıf [IDOMObject](../idomobject/)
* Sınıf [IStyleColorOwner](../istylecolorowner/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)