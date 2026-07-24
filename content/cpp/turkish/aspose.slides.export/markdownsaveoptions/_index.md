---
title: MarkdownSaveOptions
second_title: Aspose.Slides for C++ API Referansı
description: Sunumun markdown olarak kaydedilme şeklini kontrol eden seçenekleri temsil eder.
type: docs
weight: 547
url: /tr/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions sınıfı

Sunumun markdown olarak kaydedilme şeklini kontrol eden seçenekleri temsil eder.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stilindeki kayan nokta karşılaştırmasını taklit eder; burada iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN herhangi bir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stilindeki kayan nokta karşılaştırmasını taklit eder; burada iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN herhangi bir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Kaynakları içeren belgenin kaydedileceği temel yolu belirtir. Varsayılan, uygulamanın geçerli dizinidir. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okunur. |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Görselleri kaydetmek için klasör adını belirtir. Varsayılan **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Oluşturulan belgenin \r(Macintosh), \n(Unix) ya da \r\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. Varsayılan **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | **true** olarak ayarlanırsa, son Markdown çıktısındaki boş veya yalnızca boşluk içeren satırları kaldırır. Varsayılan **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrısı içeren bağlantıların atlanıp atlanmayacağını belirtir. Okur **bool**. Varsayılan değer **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini alır. Biçim, dışa aktarım sırasında slayt indeksine yerleştirilecek \"{0}\" yer tutucusunu içermelidir. Örnek: \"# Slide {0}\" \"# Slide 1\", \"# Slide 2\" gibi çıktılar üretir. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Yapıcı. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipi nesnesini nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Kaynakları içeren belgenin kaydedileceği temel yolu belirtir. Varsayılan, uygulamanın geçerli dizinidir. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Sunumu dönüştürmek için markdown spesifikasyonunu belirtir. Varsayılan **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Markdown dışa aktarımı sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Görselleri kaydetmek için klasör adını belirtir. Varsayılan **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Oluşturulan belgenin \r(Macintosh), \n(Unix) ya da \r\n(Windows) yeni satır karakterlerine sahip olup olmayacağını belirtir. Varsayılan **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | **true** olarak ayarlanırsa, son Markdown çıktısındaki boş veya sadece boşluk içeren satırları kaldırır. Varsayılan **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Oluşturulan belgenin yorumları gösterip göstermeyeceğini belirtir. Varsayılan **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Oluşturulan belgenin her slaytın numarasını gösterip göstermeyeceğini belirtir. Varsayılan **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrısı içeren bağlantıların atlanıp atlanmayacağını belirtir. **bool** yazar. Varsayılan değer **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Markdown çıktısında slayt numarası başlıkları için kullanılan biçim dizesini ayarlar. Biçim, dışa aktarım sırasında slayt indeksine yerleştirilecek \"{0}\" yer tutucusunu içermelidir. Örnek: \"# Slide {0}\" \"# Slide 1\", \"# Slide 2\" gibi çıktılar üretir. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Markdown dışa aktarımı sırasında her SVG olmayan görsel (bitmap veya metafile) için çağrılır.  
 Return **true** to use the specified *link* ,  
 or **false** to apply the default saving logic. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Markdown dışa aktarımı sırasında her SVG görseli için çağrılır.  
 Return **true** to use the specified *link* ,  
 or **false** to apply the default saving logic. |

## Açıklamalar

Örnek:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Bakınız

* Sınıf [SaveOptions](../saveoptions/)
* İsim alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)