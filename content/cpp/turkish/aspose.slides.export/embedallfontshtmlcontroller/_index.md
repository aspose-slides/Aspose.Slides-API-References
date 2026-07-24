---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for C++ API Referansı
description: WOFF formatında tüm sunum yazı tiplerini gömmek için kullanılacak biçimlendirme denetleyici sınıfı.
type: docs
weight: 1
url: /tr/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController sınıfı

Tüm sunum yazı tiplerini WOFF formatında gömmek için kullanılacak biçimlendirme denetleyici sınıfı.

```cpp
class EmbedAllFontsHtmlController : public Aspose::Slides::Export::IHtmlFormattingController
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [EmbedAllFontsHtmlController](./embedallfontshtmlcontroller/)() | Yeni bir örnek oluşturur |
|  [EmbedAllFontsHtmlController](./embedallfontshtmlcontroller/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Yeni bir örnek oluşturur |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) söz dizimini kullanarak nesneleri karşılaştırır |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere (NaN dahil) eşit olmadığı C# tarzı kayan nokta karşılaştırmasını taklit eder |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989'a göre NaN'in herhangi bir değere (NaN dahil) eşit olmadığı C# tarzı kayan nokta karşılaştırmasını taklit eder |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin string ve nullptr durumu için özelleştirmesidir |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin string durumu için özelleştirmesidir |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon bağımsız değişkeni zayıf işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır |
| virtual void [WriteAllFonts](./writeallfonts/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | [Presentation](../../aspose.slides/presentation/) içinde bulunan tüm fontları yazar |
| void [WriteDocumentEnd](./writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) override | HTML belge altbilgisini yazmak için çağrılır. Sunum dönüşümünde bir kez çağrılır |
| void [WriteDocumentStart](./writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) override | HTML belge başlığını yazmak için çağrılır. Sunum dönüşümünde bir kez çağrılır |
| virtual void [WriteFont](./writefont/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>, [System::String](../../system/string/), [System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Verileri base64 olarak HTML belgesine yazar |
| void [WriteShapeEnd](./writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Şekil çiziminden önce çağrılır. Her şekil için bir kez çağrılır. Bu fonksiyon jeneratöre bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü bir öncekinin üzerine başlatılır |
| void [WriteShapeStart](./writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) override | Şekil çiziminden önce çağrılır. Her şekil için bir kez çağrılır. Bu fonksiyon jeneratöre bir şey yazarsa, mevcut slayt görüntüsü oluşturma tamamlanır, ek HTML parçacığı eklenir ve yeni görüntü bir öncekinin üzerine başlatılır |
| void [WriteSlideEnd](./writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) override | HTML slayt altbilgisini yazmak için çağrılır. Her slayt için bir kez çağrılır |
| void [WriteSlideStart](./writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) override | HTML slayt başlığını yazmak için çağrılır. Her slayt için bir kez çağrılır |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır |

## İlgili

* Sınıf [IHtmlFormattingController](../ihtmlformattingcontroller/)
* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)