---
title: IMasterSlide
second_title: Aspose.Slides C++ API Referansı
description: Bir sunumdaki ana slaytı temsil eder.
type: docs
weight: 2926
url: /tr/aspose.slides/imasterslide/
---
## IMasterSlide sınıf

Bir sunumdaki ana slaytı temsil eder.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | Mevcut ana slayta dayanarak yeni bir ana slayt oluşturur, ona harici bir tema uygular ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Bu tema uygulanabilir nesne için etkili bir temayı döndürür. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | İki [IBaseSlide](../ibaseslide/) örneğinin eşit olup olmadığını belirler. Döndürülen değer slaytın yapısına ve statik içeriğine göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini (ör. SlideId) ve dinamik içeriği (ör. Date [Placeholder](../placeholder/) içinde geçerli tarih değeri) dikkate almaz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | Belirtilen alternatif metne sahip şeklin ilk oluşumunu bulur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | Slaytın arka planını döndürür. Salt okunur [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | Gövde metninin stilini döndürür. Salt okunur [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | Belirtilen indeksteki ActiveX kontrolünü döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | Bir slayttaki ActiveX kontrollerinin koleksiyonunu döndürür. Salt okunur [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | Slaytın özel verilerini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | Ana slayt için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | Bu ana slayta bağımlı en az bir slayt varsa true döndürür. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | Ana slaytın HeaderFooter yöneticisini döndürür. Salt okunur [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | İçerdiği köprü bağlantılarına kolay erişim sağlar. Salt okunur [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | Belirtilen indeksteki bu ana slaytın alt düzen slaytını döndürür. Salt okunur [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. Salt okunur [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | Bir slaytın adını döndürür. Okuma [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | Diğer bir metnin stilini döndürür. Salt okunur [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../ipresentation/). |
| virtual **bool** [get_Preserve](./get_preserve/)() | İlgili ana slayt, onu izleyen tüm slaytlar silindiğinde silinir mi belirler. Not: [Aspose.Slides](../) tek başına kullanılmayan bir ana slaytı asla kaldırmaz; kullanılmayan ana slaytları gerçekten kaldırmak için [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) çağırın. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | Belirtilen indeksteki şekli döndürür. Salt okunur [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | Bir slaytın şekillerini döndürür. Salt okunur [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman **false** döndürür. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | Bir slaytın kimliğini (ID) döndürür. Salt okunur **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | Belirtilen slaydın bir slayt gösterisi sırasında nasıl ilerleyeceği hakkında bilgi içeren TransitionEx nesnesini döndürür. Salt okunur [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | Ana tema yöneticisini döndürür. Salt okunur [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [IAnimationTimeLine](../ianimationtimeline/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | Başlık metninin stilini döndürür. Salt okunur [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | Bu ana slayta bağımlı tüm slaytları içeren bir dizi döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | Tüm kabul edilebilir şekillerdeki tüm paragraflardaki aynı biçimlendirmeye sahip koşulları birleştirir. |
| void [Lock](../../system/object/lock/)() | C# lock() deyimini kilitlemek için uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | Bir slaytın adını ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | İlgili ana slayt, onu izleyen tüm slaytlar silindiğinde silinir mi belirler. Not: [Aspose.Slides](../) tek başına kullanılmayan bir ana slaytı asla kaldırmaz; kullanılmayan ana slaytları gerçekten kaldırmak için [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) çağırın. Yazma **bool**. |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman **false** döndürür. Yazma **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf (weak) gösterici olarak ayarlar (paylaşımlı yerine). Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyimini kilit açmak için uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Diğer Bilgiler

* Sınıf [IBaseSlide](../ibaseslide/)
* Sınıf [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)