---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API Referansı
description: Grafik metin öğeleri için biçimlendirme özelliklerini temsil eder.
type: docs
weight: 885
url: /tr/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat sınıfı

Grafik metin öğeleri için biçimlendirme özelliklerini temsil eder.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Bir [TextFrame](../../aspose.slides/textframe/) içinde dikey çapa metnini döndürür. Oku [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Metnin otomatik sığdırma kipini döndürür. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Oku [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../../aspose.slides/nullablebool/) ise metin kutuda yatay olarak ortalanmalıdır. Oku [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Bir [TextFrame](../../aspose.slides/textframe/) içinde alt kenar boşluğunu (nokta) döndürür. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Oku **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Bir [TextFrame](../../aspose.slides/textframe/) içinde sol kenar boşluğunu (nokta) döndürür. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Oku **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Bir [TextFrame](../../aspose.slides/textframe/) içinde sağ kenar boşluğunu (nokta) döndürür. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Oku **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Bir [TextFrame](../../aspose.slides/textframe/) içinde üst kenar boşluğunu (nokta) döndürür. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Oku **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Sınırlayıcı kutu içinde uygulanan özel döndürmeyi belirtir. Belirtilmemişse, eşlik eden şeklin döndürmesi kullanılır. Belirtilmişse, şekilden bağımsız olarak uygulanır. Yani şeklin döndürmesi, metnin döndürmesinden ayrı bir şekilde eklenebilir. Bu özellik ve TextVerticalType özelliğindeki ön tanımlı dikey tipten özetlenen görsel metin döndürmesinin sonucu. Oku **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Metin yönünü belirler. Bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenen görsel metin döndürmesinin sonucu. Oku [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** if text is wrapped at [TextFrame](../../aspose.slides/textframe/)'s margins. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2007/2013). Read [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından açıklanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans, değer türü nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Bir [TextFrame](../../aspose.slides/textframe/) içinde dikey çapa metnini ayarlar. Yaz [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Metnin otomatik sığdırma kipini ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Yaz [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | [NullableBool::True](../../aspose.slides/nullablebool/) ise metin kutuda yatay olarak ortalanmalıdır. Yaz [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Bir [TextFrame](../../aspose.slides/textframe/) içinde alt kenar boşluğunu (nokta) ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Yaz **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Bir [TextFrame](../../aspose.slides/textframe/) içinde sol kenar boşluğunu (nokta) ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Yaz **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Bir [TextFrame](../../aspose.slides/textframe/) içinde sağ kenar boşluğunu (nokta) ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Yaz **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Bir [TextFrame](../../aspose.slides/textframe/) içinde üst kenar boşluğunu (nokta) ayarlar. Bu özelliğin değiştirilmesi yalnızca şu grafik bölümlerinde belirli bir etki yaratabilir: [DataLabel](../datalabel/) ve [DataLabelFormat](../datalabelformat/) (PowerPoint 2013'te tam destek; PowerPoint 2007'de renderleme için etkisi yok). Yaz **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Sınırlayıcı kutu içinde uygulanan özel döndürmeyi belirtir. Belirtilmemişse, eşlik eden şeklin döndürmesi kullanılır. Belirtilmişse, şekilden bağımsız olarak uygulanır. Yani şeklin döndürmesi, metnin döndürmesinden ayrı bir şekilde eklenebilir. Bu özellik ve TextVerticalType özelliğindeki ön tanımlı dikey tipten özetlenen görsel metin döndürmesinin sonucu. Yaz **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Metin yönünü belirler. Bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenen görsel metin döndürmesinin sonucu. Yaz [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** if text is wrapped at [TextFrame](../../aspose.slides/textframe/)'s margins. Changing of this property can produce a certain influence only for these chart parts: [DataLabel](../datalabel/) and [DataLabelFormat](../datalabelformat/) (full suport in PowerPoint 2007/2013). Write [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* İsim uzayı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)