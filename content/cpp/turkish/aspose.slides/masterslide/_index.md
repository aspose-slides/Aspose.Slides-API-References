---
title: MasterSlide
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunumda ana slaytı temsil eder.
type: docs
weight: 4473
url: /tr/aspose.slides/masterslide/
---
## MasterSlide sınıfı

Bir sunumdaki ana slaytı temsil eder.

```cpp
class MasterSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::IMasterSlide
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) override | Mevcut ana slayta dayanarak yeni bir master slayt oluşturur, ona harici bir tema uygular ve oluşturulan master slaytı tüm bağımlı slaytlara uygular. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Bu slayt için geçerli bir temayı döndürür. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | İki [IBaseSlide](../ibaseslide/) örneğinin eşit olup olmadığını belirler. Dönen değer, slaytın yapısı ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerleri ve Date [Placeholder](../placeholder/) içindeki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Slaytın arka planını döndürür. Yalnızca okuma [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() override | Gövde metninin stilini döndürür. Yalnızca okuma [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Belirtilen dizindeki ActiveX denetimini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Yalnızca okuma [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Slaytın özel verilerini döndürür. Yalnızca okuma [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | Ana slayt için çizim kılavuzlarının bir koleksiyonunu döndürür. Yalnızca okuma [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | Bu ana slayta bağımlı en az bir slayt varsa true döndürür. Yalnızca okuma **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Ana slaytın HeaderFooter yöneticisini döndürür. Yalnızca okuma [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | İçerilen köprü bağlantılarına kolay erişim sağlar. Yalnızca okuma [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | Bu ana slayt için belirtilen dizindeki alt düzen slaytını döndürür. Yalnızca okuma [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. Yalnızca okuma [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Ana slaytın adını döndürür. Okunur [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() override | Diğer bir metnin stilini döndürür. Yalnızca okuma [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | [IPresentation](../ipresentation/) arayüzünü döndürür. Yalnızca okuma [IPresentation](../ipresentation/). |
| **bool** [get_Preserve](./get_preserve/)() override | İlgili ana slaytın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: [Aspose.Slides](../) kendi başına kullanılmayan herhangi bir ana slaytı kaldırmaz, kullanılmayan ana slaytları gerçekten kaldırmak için [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) çağırın. Ok **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Belirtilen dizindeki şekli döndürür. Yalnızca okuma [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Bir slaytın şekillerini döndürür. Yalnızca okuma [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman **false** döndürür. Ok **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Bir slaytın kimliğini döndürür. Yalnızca okuma **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Belirtilen slaytın slayt gösterisi sırasında nasıl ilerlediğiyle ilgili bilgileri içeren Transition nesnesini döndürür. Yalnızca okuma [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Tema yöneticisini döndürür. Yalnızca okuma [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Animasyon zaman çizelgesi nesnesini döndürür. Yalnızca okuma [IAnimationTimeLine](../ianimationtimeline/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() override | Başlık metninin stilini döndürür. Yalnızca okuma [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | Bu ana slayta bağımlı tüm slaytları içeren bir dizi döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun karşılığıdır. Özel nesnelerin karmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının karşılığıdır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını denetler. C# 'is' operatörünün karşılığıdır. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | Tüm paragraflarda ve tüm uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Tüm paragraflarda ve tüm uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun karşılığıdır. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Ana slaytın adını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Preserve](./set_preserve/)(**bool**) override | İlgili ana slaytın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: [Aspose.Slides](../) kendi başına kullanılmayan bir ana slaytı kaldırmaz, kullanılmayan ana slaytları gerçekten kaldırmak için [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) çağırın. Yaz **bool**. |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman **false** döndürür. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun karşılığıdır. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseSlide](../baseslide/)
* Sınıf [IMasterSlide](../imasterslide/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)