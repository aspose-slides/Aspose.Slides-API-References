---
title: IDocumentProperties
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 1977
url: /tr/aspose.slides/idocumentproperties/
---
## IDocumentProperties sınıf

Bir sunumun özelliklerini temsil eder.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Tüm builtIn özelliklerinin varsayılan değerlerini temizler ve ayarlar. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Tüm özel özellikleri kaldırır. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Belirtilen adla bir özel özelliğin mevcut olup olmadığını kontrol eder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Bir uygulamanın şablonunu döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Uygulama sürümünü döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Sunumun yazarını döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Sunumun kategorisini döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Sunumun yorumlarını döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Şirket özelliğini döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Sunumun içerik durumunu döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Sunumun içerik tipini döndürür. Okunur [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Bir koleksiyonda gerçekte bulunan özel özellik sayısını döndürür. Okunur **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dir. Okunur [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Okunur [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Gizli slayt sayısını belirler. Okunur **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | HyperlinkBase belge özelliğini döndürür. Okunur [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Bir ya da daha fazla köprünün bu bölümde yalnızca bir üretici tarafından güncellendiğini belirtir. Belgeyi sonraki üretici açtığında köprü ilişkileri bu bölümde belirtilen yeni köprülerle güncellenir. Okunur **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Sunumun anahtar kelimelerini döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Sunumun en son yazdırıldığı tarihi döndürür. Okunur [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Sunumu son değiştiren kişinin adını döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Sunumun en son ne zaman değiştirildiğini döndürür. Değerler UTC'dir. Presentation.DocumentProperties durumunda yalnızca okunur (çünkü [IPresentation](../ipresentation/) nesnesi kaydedilirken dahili olarak güncellenir). [DocumentProperties](../documentproperties/) örneği aracılığıyla, [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) yöntemiyle değiştirilebilir. Lütfen [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) yöntem özetindeki örneğe bakın. |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız köprülerin güncel olduğunu, **false** olarak ayarlarsanız köprülerin eski olduğunu belirtir. Okunur **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Yönetici özelliğini döndürür. Okunur [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Belgede bulunan ses veya video kliplerinin toplam sayısını belirler. Okunur **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Uygulamanın adını döndürür. Okunur [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Not içeren slaytların sayısını belirler. Okunur **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Uygun olduğunda bir belgede bulunan paragraf sayısını belirler. Okunur **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Sunumun hedef formatını döndürür. Okunur [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Sunum revizyon numarasını döndürür. Okunur **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Belge küçük resminin görüntüleme modunu gösterir. Bu öğeyi **true** yaparsanız küçük resim ekrana ölçeklenir, **false** yaparsanız sadece ekrana sığan bölümler gösterilecek şekilde kırpılır. Okunur **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunur **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Sunum belgesindeki toplam slayt sayısını belirler. Okunur **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Sunumun konusunu döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Sunumun başlığını döndürür. Okunur [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Her belge bölümünün başlığını belirler. Bu bölümler gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Okunur [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Sunumun toplam düzenleme süresi. Okunur [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Bir belgede bulunan toplam kelime sayısını belirler. Okunur **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Belirtilen indeksteki özel özellik adını döndürür. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Özel özelliklerden adlandırılmış bir bool değer alır. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Özel özelliklerden adlandırılmış bir tam sayı değeri alır. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Özel özelliklerden adlandırılmış bir dize değeri alır. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Özel özelliklerden adlandırılmış bir float değeri alır. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Özel özelliklerden adlandırılmış bir double değeri alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Özel belge özelliklerinden hassasiyet etiketleri dizisini alır (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Belirtilen adla ilişkili özel özelliği döndürür. Okunur [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Belirtilen adla ilişkili özel özelliği ayarlar. Yazılabilir [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemeyi uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | dize durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmiş hali. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Uygulamanın şablonunu ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Sunumun yazarını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Sunumun kategorisini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Sunumun yorumlarını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Şirket özelliğini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Sunumun içerik durumunu ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Sunumun içerik tipini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Sunumun oluşturulduğu tarihi ayarlar. Değerler UTC'dir. Yazılabilir [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | HyperlinkBase belge özelliğini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Bir ya da daha fazla köprünün bu bölümde yalnızca bir üretici tarafından güncellendiğini belirtir. Belgeyi sonraki üretici açtığında köprü ilişkileri bu bölümde belirtilen yeni köprülerle güncellenir. Yazılabilir **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Sunumun anahtar kelimelerini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Sunumun en son yazdırıldığı tarihi ayarlar. Yazılabilir [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Sunumu son değiştiren kişinin adını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Sunumun en son ne zaman değiştirildiğini ayarlar. Değerler UTC'dir. Presentation.DocumentProperties durumunda yalnızca okunur (çünkü [IPresentation](../ipresentation/) nesnesi kaydedilirken dahili olarak güncellenir). [DocumentProperties](../documentproperties/) örneği aracılığıyla, [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) yöntemiyle değiştirilebilir. Lütfen [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) yöntem özetindeki örneğe bakın. |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız köprülerin güncel olduğunu, **false** olarak ayarlarsanız köprülerin eski olduğunu belirtir. Yazılabilir **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Yönetici özelliğini ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Uygulamanın adını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Sunumun hedef formatını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Sunum revizyon numarasını ayarlar. Yazılabilir **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Belge küçük resminin görüntüleme modunu ayarlar. Bu öğeyi **true** yaparsanız küçük resim ekrana ölçeklenir, **false** yaparsanız sadece ekrana sığan bölümler gösterilecek şekilde kırpılır. Yazılabilir **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını ayarlar. Yazılabilir **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Sunumun konusunu ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Sunumun başlığını ayarlar. Yazılabilir [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Sunumun toplam düzenleme süresi. Yazılabilir [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Adlandırılmış bir bool özel özelliği ayarlar. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Adlandırılmış bir tam sayı özel özelliği ayarlar. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Adlandırılmış bir dize özel özelliği ayarlar. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Adlandırılmış bir float özel özelliği ayarlar. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Adlandırılmış bir double özel özelliği ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## See Also

* Sınıf [Object](../../system/object/)
* AdAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)