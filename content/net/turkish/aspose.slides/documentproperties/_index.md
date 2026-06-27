---
title: DocumentProperties
second_title: Aspose.Slides için .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 2770
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
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Bir uygulamanın şablonunu döndürür veya ayarlar. Okuma/Yazma String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Uygulama sürümünü döndürür. Yalnızca okuma String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Sunumun yazarını döndürür veya ayarlar. Okuma/Yazma String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Sunumun kategorisini döndürür veya ayarlar. Okuma/Yazma String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Sunumun yorumlarını döndürür veya ayarlar. Okuma/Yazma String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Şirket özelliğini döndürür veya ayarlar. Okuma/Yazma String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Sunumun içerik durumunu döndürür veya ayarlar. Okuma/Yazma String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Sunumun içerik tipini döndürür veya ayarlar. Okuma/Yazma String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Bir koleksiyonda bulunan özel özelliklerin sayısını döndürür. Yalnızca okuma Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dir. Okuma/Yazma DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Belge bölümlerinin gruplandırılmasını ve her grup içindeki bölüm sayısını gösterir. Yalnızca okuma IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Bir sunum belgesindeki gizli slaytların sayısını döndürür. Yalnızca okuma Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini döndürür veya ayarlar. Okuma/Yazma String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Bu bölümdeki bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Bir sonraki üretici bu belgeyi açtığında köprü ilişkileri bu bölümde belirtilen yeni köprülerle güncellenecektir. Okuma/Yazma Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. Okuma/Yazma Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Sunumun anahtar kelimelerini döndürür veya ayarlar. Okuma/Yazma String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; } | Bir sunumun en son yazdırıldığı tarihi döndürür. Okuma/Yazma DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okuma/Yazma String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Bir sunumun en son ne zaman değiştirildiğini döndürür. Değerler UTC'dir. Presentation.DocumentProperties durumunda yalnızca okuma (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemi tarafından döndürülen DocumentProperties örneği üzerinden değiştirilebilir. [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntem özetindeki örneğe bakınız. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Köprülerin güncel olmadığını belirtmek için bu öğeyi **false** olarak ayarlayın. Okuma/Yazma Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Yönetici özelliğini döndürür veya ayarlar. Okuma/Yazma String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Belgede bulunan ses veya video kliplerinin toplam sayısını döndürür. Yalnızca okuma Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Uygulamanın adını döndürür veya ayarlar. Okuma/Yazma String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Not içeren bir sunumdaki slayt sayısını döndürür. Yalnızca okuma Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Uygun olduğunda bir belgede bulunan paragraf sayısını toplam olarak döndürür. Yalnızca okuma Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Sunumun amaçlanan biçimini döndürür veya ayarlar. Okuma/Yazma String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını döndürür veya ayarlar. Okuma/Yazma Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Belge küçük resminin görüntüleme modunu gösterir. Ölçeklendirmeyi etkinleştirmek için bu öğeyi **true** olarak ayarlayın. Kırpmayı etkinleştirerek yalnızca ekrana uyan bölümleri göstermek için bu öğeyi **false** olarak ayarlayın. Okuma/Yazma Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okuma/Yazma Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Bir sunum belgesindeki toplam slayt sayısını döndürür. Yalnızca okuma Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Sunumun konusunu döndürür veya ayarlar. Okuma/Yazma String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Sunumun başlığını döndürür veya ayarlar. Okuma/Yazma String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Her belge bölümünün başlığını belirtir. Bu bölümler belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Yalnızca okuma string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Bir sunumun toplam düzenleme süresi. Okuma/Yazma TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını döndürür. Yalnızca okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Tüm yerleşik özelliklerin varsayılan değerlerini temizler ve ayarlar. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Geçerli nesneyi klonlar |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Geçerli nesneyi klonlar |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Belirtilen isimde bir özel özelliğin varlığını denetler. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Belirtilen indeksdeki özel özelliğin adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden adlandırılmış bir boolean değer alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden adlandırılmış bir double değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden adlandırılmış bir float değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden adlandırılmış bir tam sayı değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden adlandırılmış bir string değeri alır. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Belirtilen isimle ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Adlandırılmış bir double özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Adlandırılmış bir float özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Adlandırılmış bir tam sayı özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Adlandırılmış bir string özel özelliği ayarlar. |

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumu'nun yerleşik Özelliklerine nasıl erişileceğini gösterir.

```csharp
[C#]
// Sunumu temsil eden Presentation sınıfını oluşturur
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluşturur
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Yerleşik özellikleri gösterir
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
// Sunumu temsil eden Presentation sınıfını oluşturur
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluşturur
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Yerleşik özellikleri ayarlar
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Sunumunuzu bir dosyaya kaydeder
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* arayüz [IDocumentProperties](../idocumentproperties)
* arayüz [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->