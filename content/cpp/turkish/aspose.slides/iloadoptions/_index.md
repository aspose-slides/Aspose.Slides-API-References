---
title: ILoadOptions
second_title: Aspose.Slides C++ API Referansı
description: Bir sunum yüklenirken ek seçenekleri (örneğin biçim veya varsayılan yazı tipi) belirtmeye olanak tanır.
type: docs
weight: 2796
url: /tr/aspose.slides/iloadoptions/
---
## ILoadOptions sınıfı

Bir sunum yüklenirken ek seçenekleri (ör. biçim veya varsayılan yazı tipi) belirtmeye olanak tanır.

```cpp
class ILoadOptions : public virtual System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir; ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir; ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | Binary Large Objects (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder, örneğin geçici dosyaların kullanılması veya bellek içindeki maksimum BLOB baytları gibi. Bu seçenekler belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | Kaynak yazı tipi bulunamadığında kullanılan Düzenli (Regular) yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | Sunum metni için varsayılan dili döndürür. [System::String](../../system/string/) okunur. |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | Sunum yüklenirken [Aspose.Slides](../) tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | Sunum tarafından kullanılacak dış yazı tipleri kaynaklarını belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | Kesinti isteklerini izlemek için kullanılan belirteç. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | Yüklenecek sunumun biçimini döndürür. [Slides::LoadFormat](../loadformat/) okunur. |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. true değeri, şifreli bir sunum dosyasından sadece belge özelliklerinin yüklenmesi gerektiği ve parolanın göz ardı edileceği anlamına gelir. false değeri, tüm şifreli sunumun doğru parola kullanılarak yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. **bool** okunur. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Parolayı alır. [System::String](../../system/string/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü döndürür. [IResourceLoadingCallback](../iresourceloadingcallback/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | Ek tablolar davranışını belirtmek için kullanılabilecek seçenekleri temsil eder. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun bir benzeridir. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir benzeridir. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün bir benzeridir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun bir benzeridir. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | Binary Large Objects (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder, örneğin geçici dosyaların kullanılması veya bellek içindeki maksimum BLOB baytları gibi. Bu seçenekler belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | Kaynak yazı tipi bulunamadığında kullanılan Düzenli (Regular) yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | Sunum metni için varsayılan dili ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | [Aspose.Slides](../) sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | Sunum tarafından kullanılacak dış yazı tipleri kaynaklarını belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | Kesinti isteklerini izlemek için kullanılan belirteç. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | Yüklenecek sunumun biçimini ayarlar. [Slides::LoadFormat](../loadformat/) yazar. |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. true değeri, şifreli bir sunum dosyasından sadece belge özelliklerinin yüklenmesi gerektiği ve parolanın göz ardı edileceği anlamına gelir. false değeri, tüm şifreli sunumun doğru parola kullanılarak yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. **bool** yazar. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Parolayı ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü ayarlar. [IResourceLoadingCallback](../iresourceloadingcallback/) yazar. |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | Ek tablolar davranışını belirtmek için kullanılabilecek seçenekleri temsil eder. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi ayarlar. [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun bir benzeridir. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Ayrıca

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)