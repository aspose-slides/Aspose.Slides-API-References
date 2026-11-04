---
title: DocumentProperties
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 2810
url: /tr/aspose.slides/documentproperties/
---
## DocumentProperties sınıfı

Bir sunumun özelliklerini temsil eder.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DocumentProperties](documentproperties)() | Sınıf [`DocumentProperties`](../documentproperties)'nin yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Uygulamanın şablonunu döndürür veya ayarlar. Okunur/Yazılır String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Uygulama sürümünü döndürür. Salt okunur String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Sunumun yazarını döndürür veya ayarlar. Okunur/Yazılır String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Sunumun kategorisini döndürür veya ayarlar. Okunur/Yazılır String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Sunumun yorumlarını döndürür veya ayarlar. Okunur/Yazılır String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Şirket özelliğini döndürür veya ayarlar. Okunur/Yazılır String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Sunumun içerik durumunu döndürür veya ayarlar. Okunur/Yazılır String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Sunumun içerik türünü döndürür veya ayarlar. Okunur/Yazılır String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Bir koleksiyonda gerçekte bulunan özel özelliklerin sayısını döndürür. Salt okunur Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dir. Okunur/Yazılır DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir. Salt okunur IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Sunum belgesindeki gizli slaytların sayısını döndürür. Salt okunur Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunur/Yazılır String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Sonraki üreticinin bu belgeyi açması, bu bölümde belirtilen yeni köprülerle köprü ilişkilerini güncelleyecektir. Okunur/Yazılır Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. Okunur/Yazılır Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Sunumun anahtar kelimelerini döndürür veya ayarlar. Okunur/Yazılır String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Sunumun en son yazdırıldığı tarihi döndürür. Okunur/Yazılır DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunur/Yazılır String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Sunumun en son ne zaman değiştirildiğini döndürür. Değerler UTC'dir. Presentation.DocumentProperties durumunda salt okunurdur (çünkü IPresentation nesnesi kaydetme sürecinde dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemiyle dönen DocumentProperties örneği aracılığıyla değiştirilebilir. [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntemi özetindeki örneğe bakınız. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Köprülerin güncel olmadığını belirtmek için bu öğeyi **false** olarak ayarlayın. Okunur/Yazılır Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Yönetici özelliğini döndürür veya ayarlar. Okunur/Yazılır String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Belgede bulunan ses veya video kliplerinin toplam sayısını döndürür. Salt okunur Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Uygulamanın adını döndürür veya ayarlar. Okunur/Yazılır String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Not içeren sunum slaytlarının sayısını döndürür. Salt okunur Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Belgede bulunan toplam paragraf sayısını döndürür (uygulanabilir ise). Salt okunur Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Sunumun istenen biçimini döndürür veya ayarlar. Okunur/Yazılır String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını döndürür veya ayarlar. Okunur/Yazılır Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Belge önizlemesinin görüntüleme modunu gösterir. Önizlemenin ekrana ölçeklenmesini etkinleştirmek için bu öğeyi **true** olarak ayarlayın. Önizlemenin yalnızca ekrana uyan bölümleri gösterecek şekilde kırpılmasını etkinleştirmek için bu öğeyi **false** olarak ayarlayın. Okunur/Yazılır Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunur/Yazılır Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Sunum belgesindeki toplam slayt sayısını döndürür. Salt okunur Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Sunumun konusunu döndürür veya ayarlar. Okunur/Yazılır String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Sunumun başlığını döndürür veya ayarlar. Okunur/Yazılır String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Her belge parçasının başlığını belirler. Bu parçalar belge parçaları değildir; belge bölümlerinin kavramsal temsilleridir. Salt okunur string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Sunumun toplam düzenleme süresi. Okunur/Yazılır TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını döndürür. Salt okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Tüm builtIn özelliklerini temizler ve varsayılan değerleri ayarlar. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Geçerli nesneyi klonlar. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Geçerli nesneyi klonlar. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Belirtilen indeksteki özel özellik adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden adlandırılmış bir Boolean değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden adlandırılmış bir DateTime değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden adlandırılmış bir double değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden adlandırılmış bir float değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden adlandırılmış bir integer değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden adlandırılmış bir string değerini alır. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) hassasiyet etiketlerinin bir dizisini alır. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Adlandırılmış bir Boolean özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Adlandırılmış bir double özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Adlandırılmış bir float özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Adlandırılmış bir integer özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Adlandırılmış bir string özel özelliği ayarlar. |

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumu'nun yerleşik Özelliklerine nasıl erişileceğini gösterir.

```csharp
[C#]
// Sunumu temsil eden Presentation sınıfının bir örneğini oluştur.
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluştur.
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Yerleşik özellikleri göster.
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Aşağıdaki örnek, PowerPoint Sunumu'nun yerleşik Özelliklerini nasıl değiştireceğinizi gösterir.

```csharp
[C#]
// Sunumu temsil eden Presentation sınıfının bir örneğini oluştur.
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluştur.
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Yerleşik özellikleri ayarla
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Sunumunuzu bir dosyaya kaydedin
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* arayüz [IDocumentProperties](../idocumentproperties)
* arayüz [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->