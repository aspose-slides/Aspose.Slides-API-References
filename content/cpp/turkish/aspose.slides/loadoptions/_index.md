---
title: LoadOptions
second_title: Aspose.Slides for C++ API Referansı
description: Sunum yüklenirken ek seçenekleri (örneğin format veya varsayılan yazı tipi) belirlemenizi sağlar.
type: docs
weight: 4395
url: /tr/aspose.slides/loadoptions/
---
## LoadOptions sınıf

Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Geçici dosyaların kullanılması veya bellek içinde maksimum BLOB baytı gibi Binary Large Objects (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketim oranını ayarlamayı amaçlar. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini döndürür. Okuyun [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | Sunum metni için varsayılan dili döndürür. Okuyun [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | [Aspose.Slides](../)'nin sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | Sunumun kullanacağı harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | Kesinti isteklerini izlemek için kullanılan token. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Yüklenecek bir sunumun formatını döndürür. Okuyun [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. true değeri, şifreli bir sunum dosyasından yalnızca belge özelliklerinin yüklenmesi ve şifrenin göz ardı edilmesi gerektiği anlamına gelir. false değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri genel değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. **bool** okuyun. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Şifreyi alır. Okuyun [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü döndürür. Okuyun [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | Elektronik tablolar için seçenekleri alır. Örneğin, bu seçenekler grafikler için formül hesaplamalarını etkiler. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür. Okuyun [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| [LoadOptions](./loadoptions/)() | Yeni varsayılan yükleme seçenekleri oluşturur. |
| [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | Yeni yükleme seçenekleri oluşturur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Direkt olarak çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özel bir türüdür. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özel bir türüdür. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Geçici dosyaların kullanılması veya bellek içinde maksimum BLOB baytı gibi Binary Large Objects (BLOBs) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketim oranını ayarlamayı amaçlar. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini ayarlar. Yazın [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini ayarlar. Yazın [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini ayarlar. Yazın [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | Sunum metni için varsayılan dili ayarlar. Yazın [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | [Aspose.Slides](../)'nin sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | Sunumun kullanacağı harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun ömrü boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz. |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | Kesinti isteklerini izlemek için kullanılan token. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | Yüklenecek bir sunumun formatını ayarlar. Yazın [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. true değeri, şifreli bir sunum dosyasından yalnızca belge özelliklerinin yüklenmesi ve şifrenin göz ardı edilmesi gerektiği anlamına gelir. false değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri genel değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. **bool** yazın. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Şifreyi ayarlar. Yazın [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü ayarlar. Yazın [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | Elektronik tablolar için seçenekleri alır. Örneğin, bu seçenekler grafikler için formül hesaplamalarını etkiler. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi ayarlar. Yazın [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon bağımsız değişkeni zayıf bir işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Direkt olarak çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [ILoadOptions](../iloadoptions/)
* AdAlanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)