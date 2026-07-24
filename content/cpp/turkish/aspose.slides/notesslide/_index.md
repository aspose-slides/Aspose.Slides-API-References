---
title: NotesSlide
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunumda not slaytını temsil eder.
type: docs
weight: 4564
url: /tr/aspose.slides/notesslide/
---
## NotesSlide sınıfı

Bir sunumda not slaytını temsil eder.

```cpp
class NotesSlide : public Aspose::Slides::BaseSlide,
                   public Aspose::Slides::INotesSlide
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Bu slayt için etkin bir temayı döndürür. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | İki [IBaseSlide](../ibaseslide/) örnek eşit mi belirler. Döndürülen değer slaytın yapısı ve statik içeriğe göre hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşit olduğunda iki slayt eşittir. Karşılaştırma, SlideId gibi benzersiz tanımlayıcı değerleri ve Date [Placeholder](../placeholder/) içindeki mevcut tarih değeri gibi dinamik içeriği dikkate almaz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Belirtilen alternatif metne sahip şeklin ilk örneğini bulur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Slaytın arka planını döndürür. Salt okunur [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Belirtilen indeksteki ActiveX denetimini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Bir slayttaki ActiveX denetimlerinin koleksiyonunu döndürür. Salt okunur [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Slaytın özel verisini döndürür. Salt okunur [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Not slaytının HeaderFooter yöneticisini döndürür. Salt okunur [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | İçerilen köprüleri kolayca erişilebilir hâle getirir. Salt okunur [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | Bir slaytın adını döndürür. Okunur [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() override | Varsa not metni içeren bir [TextFrame](../textframe/) döndürür. Salt okunur [ITextFrame](../itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() override | Üst slaytı döndürür. Salt okunur [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | [IPresentation](../ipresentation/) arayüzünü döndürür. Salt okunur [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Belirtilen indeksteki şekli döndürür. Salt okunur [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Bir slayttaki şekilleri döndürür. Salt okunur [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Usta slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Bir slaytın kimliğini döndürür. Salt okunur **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Belirtilen slaytın slayt gösterisi sırasında nasıl ilerlediği hakkında bilgi içeren Transition nesnesini döndürür. Salt okunur [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Geçersiz kılan tema yöneticisini döndürür. Salt okunur [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Animasyon zaman çizelgesi nesnesini döndürür. Salt okunur [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | Tüm paragraf ve uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Tüm paragraf ve uygun şekillerde aynı biçimlendirmeye sahip koşulları birleştirir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme özelliğini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için uzmanlaştırması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için uzmanlaştırması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | Bir slaytın adını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Usta slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit kaldırma özelliğini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Diğer Bağlantılar

* Sınıf [BaseSlide](../baseslide/)
* Sınıf [INotesSlide](../inotesslide/)
* İsim Uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)