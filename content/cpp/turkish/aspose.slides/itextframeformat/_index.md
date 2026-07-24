---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API Referansı
description: TextFrame'in biçimlendirme özelliklerini içerir.
type: docs
weight: 4083
url: /tr/aspose.slides/itextframeformat/
---
## ITextFrameFormat sınıf

[TextFrame](../textframe/)'nin biçimlendirme özelliklerini içerir.

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili kullanım içindir. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | [TextFrame](../textframe/) içinde dikey çapa metnini döndürür. Oku [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Metnin otomatik sığdırma modunu döndürür. Oku [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | [NullableBool::True](../nullablebool/) ise metin kutunun içinde yatay olarak ortalanmalıdır. Oku [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Metin alanındaki sütun sayısını döndürür. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0, tanımsız değeri gösterir. Oku **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Metin alanındaki sütunlar arasındaki boşluğu (point cinsinden) döndürür. Bu yalnızca birden fazla sütun mevcut olduğunda uygulanır. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Oku **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Metnin tamamen 3D sahneden dışarıda tutulup tutulmadığını döndürür veya ayarlar. Oku **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | [TextFrame](../textframe/) içinde alt kenar boşluğunu (point) döndürür. Oku **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | [TextFrame](../textframe/) içinde sol kenar boşluğunu (point) döndürür. Oku **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | [TextFrame](../textframe/) içinde sağ kenar boşluğunu (point) döndürür. Oku **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | [TextFrame](../textframe/) içinde üst kenar boşluğunu (point) döndürür. Oku **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Metin içinde sınırlayıcı kutuya uygulanan özel rotasyonu belirtir. Belirtilmezse, eşlik eden şeklin dönüşü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şeklin döndürülmesi, metnin de ayrıca döndürülmesi anlamına gelir. Görsel metin dönüşünün sonuç değeri bu özellik ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetidir. Oku **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Metnin stilini döndürür. Salt okunur [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Metin yönelimini belirler. Görsel metin dönüşünün sonuç değeri bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenir. Oku [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Metin için 3D efekt özelliklerini temsil eden [ThreeDFormat](../threedformat/) nesnesini döndürür. Salt okunur [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Metin kırpma şeklini alır. Oku [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | [TextFrame](../textframe/) kenar boşluklarında metin kırpıldıysa **True** döndürür. Oku [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Uygulanan kalıtımla etkili metin çerçevesi biçimlendirme verisini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Direkt olarak çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans şeklinde karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel türevi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel bir türevi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | [TextFrame](../textframe/) içinde dikey çapa metnini ayarlar. Yaz [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Metnin otomatik sığdırma modunu ayarlar. Yaz [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | [NullableBool::True](../nullablebool/) ise metin kutunun içinde yatay olarak ortalanmalıdır. Yaz [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Metin alanındaki sütun sayısını ayarlar. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Değer 0, tanımsız değeri gösterir. Yaz **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Metin alanındaki sütunlar arasındaki boşluğu (point) ayarlar. Bu yalnızca birden fazla sütun mevcut olduğunda geçerlidir. Bu değer pozitif bir sayı olmalıdır. Aksi takdirde değer sıfıra ayarlanır. Yaz **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Metnin tamamen 3D sahneden dışarıda tutulup tutulmadığını döndürür veya ayarlar. Yaz **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | [TextFrame](../textframe/) içinde alt kenar boşluğunu (point) ayarlar. Yaz **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | [TextFrame](../textframe/) içinde sol kenar boşluğunu (point) ayarlar. Yaz **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | [TextFrame](../textframe/) içinde sağ kenar boşluğunu (point) ayarlar. Yaz **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | [TextFrame](../textframe/) içinde üst kenar boşluğunu (point) ayarlar. Yaz **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Metin içinde sınırlayıcı kutuya uygulanan özel rotasyonu belirtir. Belirtilmezse, eşlik eden şeklin dönüşü kullanılır. Belirtilirse, bu şekilden bağımsız olarak uygulanır. Yani şeklin döndürülmesi, metnin de ayrıca döndürülmesi anlamına gelir. Görsel metin dönüşünün sonuç değeri bu özellik ve TextVerticalType özelliğindeki önceden tanımlı dikey tipin özetidir. Yaz **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Metin yönelimini belirler. Görsel metin dönüşünün sonuç değeri bu özellik ve RotationAngle özelliğindeki özel açıdan özetlenir. Yaz [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Metin kırpma şeklini ayarlar. Yaz [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | [TextFrame](../textframe/) kenar boşluklarında metin kırpıldıysa **True** döndürür. Yaz [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilit açma işlemini uygular. Direkt olarak çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)