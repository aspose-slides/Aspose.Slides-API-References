---
title: BulletFormat
second_title: Aspose.Slides için C++ API Referansı
description: Paragraf madde işareti biçimlendirme özelliklerini temsil eder.
type: docs
weight: 248
url: /tr/aspose.slides/bulletformat/
---
## BulletFormat sınıfı

Paragraf madde işareti biçimlendirme özelliklerini temsil eder.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Varsayılan sıfır olmayan kaymaları, madde işaretleri etkin olduğunda (PowerPoint'in paragraf madde işaretleri/numaralandırmasını etkinleştirdiğinde yaptığı gibi) etkili paragraf Indent ve MarginLeft değerleri için ayarlar. Madde işaretleri devre dışı bırakıldığında sadece paragraf Indent ve MarginLeft değerlerini sıfırlar (PowerPoint'in paragraf madde işaretleri/numaralandırmasını devre dışı bıraktığında yaptığı gibi). Girinti kaymaları, geçerli madde işareti bağlamına göre uygulanır - IBulletFormat::get(set)_Type, .NumberedBulletStyle ve ilk bölümün FontHeight'i. Sıfır olmayan girinti kaymaları, geçerli paragrafın etkili Indent ve MarginLeft değerlerine uygulanır (sonuç değerlerini yerel değerler yapar). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| char16_t [get_Char](./get_char/)() override | Miras almadan bir paragrafın madde işareti karakterini döndürür. **wchar_t** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Miras almadan bir paragrafın madde işareti renk formatını döndürür. Yalnızca okuma [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Miras almadan bir paragrafın madde işareti yazı tipini döndürür. Okunur [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Miras almadan bir paragrafın madde işareti yüksekliğini döndürür. std::numeric_limits<float>::quiet_NaN() değeri, madde işaretinin yüksekliğini paragraftaki ilk bölümden devraldığını belirler. **float** okunur. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümlerden miras alıp almadığını belirler. **[NullableBool::True](../nullablebool/)** madde işareti kendi rengi varsa ve **[NullableBool::False](../nullablebool/)** madde işareti renk miras alıyorsa. [NullableBool](../nullablebool/) okunur. |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Madde işaretinin kendi yazı tipine sahip olup olmadığını veya paragraftaki ilk bölümlerden miras alıp almadığını belirler. **[NullableBool::True](../nullablebool/)** madde işareti kendi yazı tipine sahipse ve **[NullableBool::False](../nullablebool/)** madde işareti yazı tipini ilk bölümden miras alıyorsa. [NullableBool](../nullablebool/) okunur. |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Miras almadan numaralı madde işaretleri grubunda kullanılan ilk sayıyı döndürür. **int16_t** okunur. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Miras almadan numaralı bir madde işaretinin stilini döndürür. [Slides::NumberedBulletStyle](../numberedbulletstyle/) okunur. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. Yalnızca okuma [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. Yalnızca okuma [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Miras almadan bir paragrafta madde işareti olarak kullanılan resmi döndürür. Yalnızca okuma [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Miras almadan bir paragrafın madde işareti tipini döndürür. [BulletType](../bullettype/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Miras uygulandıktan sonra etkili madde işareti biçimlendirme verisini alır. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Hash kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için uzmanlaşması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumuna özel bir uzmanlaşması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_Char](./set_char/)(char16_t) override | Miras almadan bir paragrafın madde işareti karakterini ayarlar. **wchar_t** yazılır. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Miras almadan bir paragrafın madde işareti yazı tipini ayarlar. [IFontData](../ifontdata/) yazılır. |
| void [set_Height](./set_height/)(**float**) override | Miras almadan bir paragrafın madde işareti yüksekliğini ayarlar. std::numeric_limits<float>::quiet_NaN() değeri, madde işaretinin yüksekliğini paragraftaki ilk bölümden devraldığını belirler. **float** yazılır. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Madde işaretinin kendi renginin olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **[NullableBool::True](../nullablebool/)** madde işareti kendi rengi ise ve **[NullableBool::False](../nullablebool/)** madde işareti renk miras alıyorsa. [NullableBool](../nullablebool/) yazılır. |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Madde işaretinin kendi yazı tipine sahip olup olmadığını veya paragraftaki ilk bölümden miras alıp almadığını belirler. **[NullableBool::True](../nullablebool/)** madde işareti kendi yazı tipine sahipse ve **[NullableBool::False](../nullablebool/)** madde işareti yazı tipini ilk bölümden miras alıyorsa. [NullableBool](../nullablebool/) yazılır. |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Miras almadan numaralı madde işareti grubunda kullanılan ilk sayıyı ayarlar. **int16_t** yazılır. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Miras almadan numaralı bir madde işaretinin stilini ayarlar. [Slides::NumberedBulletStyle](../numberedbulletstyle/) yazılır. |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Miras almadan bir paragrafın madde işareti tipini ayarlar. [BulletType](../bullettype/) yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını ortak yerine zayıf bir işaretçiye ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [PVIObject](../pviobject/)
* Sınıf [IBulletFormat](../ibulletformat/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)