---
title: DocumentProperties
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 794
url: /tr/aspose.slides/documentproperties/
---
## DocumentProperties sınıfı


Bir sunumun özelliklerini temsil eder.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Tüm builtIn özellikleri için varsayılan değerleri temizler ve ayarlar. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Tüm özel özellikleri kaldırır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Geçerli nesneyi kopyalar |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Geçerli nesneyi kopyalar |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Belirtilen isimle bir özel özelliğin varlığını denetler. |
|  [DocumentProperties](./documentproperties/)() | [DocumentProperties](./) sınıfının yeni bir örneğini başlatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğine göre karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmasa da iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Bir uygulamanın şablonunu döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Uygulama sürümünü döndürür. Salt Okunur [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Sunumun yazarını döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Sunumun kategorisini döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Sunumun yorumlarını döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Şirket özelliğini döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Sunumun içerik durumunu döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Sunumun içerik türünü döndürür. Okuyun [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Bir koleksiyonda gerçekte bulunan özel niteliklerin sayısını döndürür. Salt Okunur **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dir. Okuyun [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir. Salt Okunur [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Sunum belgesindeki gizli slaytların sayısını döndürür. Salt Okunur **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | HyperlinkBase belge özelliğini döndürür. Okuyun [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Bu kısımda bir veya daha fazla köprünün yalnızca bu kısımda bir üretici tarafından güncellendiğini belirtir. Bu belgeyi bir sonraki üretici açtığında, köprü ilişkileri bu kısımda belirtilen yeni köprülerle güncellenecektir. Okuyun **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Sunumun anahtar kelimelerini döndürür. Okuyun [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Sunumun en son yazdırıldığı tarihi döndürür. Okuyun [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Sunumu en son değiştiren kişinin adını döndürür. Okuyun [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Sunumun en son değiştirildiği tarihi döndürür. Değerler UTC'dir. [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) durumunda salt okunur (çünkü [IPresentation](../ipresentation/) nesne kaydetme sürecinde dahili olarak güncellenecektir). [DocumentProperties](./) örneği aracılığıyla, [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) yöntemiyle değiştirilebilir. Lütfen [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) yöntem özetindeki örneğe bakın. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu belirtmek için bu öğeyi **true** yapın. Köprülerin eski olduğunu belirtmek için bu öğeyi **false** yapın. Okuyun **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Yönetici özelliğini döndürür. Okuyun [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Belgede bulunan ses veya video kliplerinin toplam sayısını döndürür. Salt Okunur **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Uygulamanın adını döndürür. Okuyun [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Not içeren slaytların sayısını döndürür. Salt Okunur **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Uygulanabiliyorsa belgedeki paragraf sayısını döndürür. Salt Okunur **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Sunumun hedef formatını döndürür. Okuyun [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Sunum revizyon numarasını döndürür. Okuyun **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Belge küçük resminin görüntüleme kipini belirler. Küçük resmin ekrana ölçeklenmesini etkinleştirmek için bu öğeyi **true** yapın. Küçük resmin yalnızca ekrana uyan bölümlerini göstermek için kırpılmasını etkinleştirmek amacıyla bu öğeyi **false** yapın. Okuyun **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Sunumun birden çok kişi arasında paylaşılıp paylaşılmadığını belirler. Okuyun **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Sunum belgesindeki toplam slayt sayısını döndürür. Salt Okunur **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Sunumun konusunu döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Sunumun başlığını döndürür. Okuyun [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Her belge bölümünün başlığını belirtir. Bu bölümler gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Salt Okunur [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Sunumun toplam düzenleme süresi. Okuyun [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Belgede bulunan toplam kelime sayısını döndürür. Salt Okunur **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Belirtilen indeksdeki özel özellik adını döndürür. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Özel niteliklerden bir adlandırılmış boolean değerini alır. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Özel niteliklerden bir adlandırılmış tam sayı değerini alır. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Özel niteliklerden bir adlandırılmış DateTime değerini alır. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Özel niteliklerden bir adlandırılmış dize değerini alır. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Özel niteliklerden bir adlandırılmış float değerini alır. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Özel niteliklerden bir adlandırılmış double değerini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketleri dizisini alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Belirtilen isimle ilişkili özel özelliği döndürür. Okuyun [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen isimle ilişkili özel özelliği ayarlar. Yaz [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefType tarafından tanımlanan tipe ait bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesi. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Belirtilen isimle ilişkili bir özel özelliği kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Bir uygulamanın şablonunu ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Sunumun yazarını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Sunumun kategorisini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Sunumun yorumlarını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Şirket özelliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Sunumun içerik durumunu ayarlar. Yaz [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Sunumun içerik türünü ayarlar. Yaz [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Sunumun oluşturulduğu tarihi ayarlar. Değerler UTC'dir. Yaz [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | HyperlinkBase belge özelliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Bu kısımda bir veya daha fazla köprünün yalnızca bu kısımda bir üretici tarafından güncellendiğini belirtir. Bu belgeyi bir sonraki üretici açtığında, köprü ilişkileri bu kısımda belirtilen yeni köprülerle güncellenecektir. Yaz **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Sunumun anahtar kelimelerini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Sunumun en son yazdırıldığı tarihi ayarlar. Yaz [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Sunumu en son değiştiren kişinin adını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Sunumun en son değiştirildiği tarihi ayarlar. Değerler UTC'dir. [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) durumunda salt okunur (çünkü [IPresentation](../ipresentation/) nesne kaydetme sürecinde dahili olarak güncellenecektir). [DocumentProperties](./) örneği aracılığıyla, [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) yöntemiyle değiştirilebilir. Lütfen [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) yöntem özetindeki örneğe bakın. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu belirtmek için bu öğeyi **true** yapın. Köprülerin eski olduğunu belirtmek için bu öğeyi **false** yapın. Yaz **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Yönetici özelliğini ayarlar. Yaz [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Uygulamanın adını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Sunumun hedef formatını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Sunum revizyon numarasını ayarlar. Yaz **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Belge küçük resminin görüntüleme kipini belirler. Küçük resmin ekrana ölçeklenmesini etkinleştirmek için bu öğeyi **true** yapın. Küçük resmin yalnızca ekrana uyan bölümlerini göstermek için kırpılmasını etkinleştirmek amacıyla bu öğeyi **false** yapın. Yaz **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Sunumun birden çok kişi arasında paylaşılıp paylaşılmadığını belirler. Yaz **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Sunumun konusunu ayarlar. Yaz [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Sunumun başlığını ayarlar. Yaz [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Sunumun toplam düzenleme süresi. Yaz [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Adlandırılmış bir boolean özel özelliği ayarlar. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Adlandırılmış bir tam sayı özel özelliği ayarlar. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Adlandırılmış bir dize özel özelliği ayarlar. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Adlandırılmış bir float özel özelliği ayarlar. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Adlandırılmış bir double özel özelliği ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | N.ş. şablon bağımsızını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. İşaretçilerin konteynerlerde zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesneleri dizeye dönüştürmeyi sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Açıklamalar


Aşağıdaki örnek, PowerPoint [Presentation](../presentation/)'nin yerleşik Özelliklerine nasıl erişileceğini gösterir. 
```cpp
// Sunumu temsil eden Presentation sınıfını örnekle
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 Aşağıdaki örnek, PowerPoint [Presentation](../presentation/)'nin yerleşik Özelliklerini nasıl değiştirileceğini gösterir. 
```cpp
// Sunumu temsil eden Presentation sınıfını örnekle
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluştur
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Yerleşik özellikleri ayarla
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Sunumunuzu bir dosyaya kaydedin
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Sınıf [IDocumentProperties](../idocumentproperties/)
* Sınıf [IGenericCloneable](../igenericcloneable/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)