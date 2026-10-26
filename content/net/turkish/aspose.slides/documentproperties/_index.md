---
title: DocumentProperties
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 2790
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
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Bir uygulamanın şablonunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Uygulama sürümünü alır. Salt-okunur String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Bir sunumun yazarını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Bir sunumun kategorisini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Bir sunumun yorumlarını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Şirket özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Bir sunumun içerik durumunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Bir sunumun içerik tipini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Bir koleksiyonda gerçekte bulunan özel özelliklerin sayısını alır. Salt-okunur Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Bir sunumun oluşturulma tarihini alır. Değerler UTC cinsindendir. Okunabilir/Yazılabilir DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Salt-okunur IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Bir sunum belgesindeki gizli slayt sayısını alır. Salt-okunur Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Bir sonraki üreticinin bu belgeyi açması, bu bölümde belirtilen yeni köprülerle köprü ilişkilerini güncelleyecektir. Okunabilir/Yazılabilir Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Belirtilen adla ilişkili özel özelliği alır veya ayarlar. Okunabilir/Yazılabilir Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Bir sunumun anahtar kelimelerini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Bir sunumun en son ne zaman yazdırıldığını alır. Okunabilir/Yazılabilir DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Bir sunumu en son değiştiren kişinin adını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Bir sunumun en son ne zaman değiştirildiğini alır. Değerler UTC cinsindendir. Presentation.DocumentProperties durumunda salt-okunur (çünkü IPresentation nesnesi kaydetme sürecinde dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemi tarafından döndürülen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntemi özetindeki örneğe bakın. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu göstermek için bu öğeyi **true** olarak ayarlayın. Köprülerin güncel olmadığını göstermek için bu öğeyi **false** olarak ayarlayın. Okunabilir/Yazılabilir Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Yönetici özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Belgede bulunan ses veya video kliplerinin toplam sayısını alır. Salt-okunur Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Uygulamanın adını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Not içeren bir sunumdaki slayt sayısını alır. Salt-okunur Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Uygun olduğunda bir belgede bulunan paragraf sayısını alır. Salt-okunur Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Bir sunumun amaçlanan biçimini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını alır veya ayarlar. Okunabilir/Yazılabilir Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Belge küçük resminin görüntüleme modunu gösterir. Bu öğeyi **true** olarak ayarlayarak belge küçük resminin ekrana ölçeklenmesini etkinleştirin. Bu öğeyi **false** olarak ayarlayarak belge küçük resminin yalnızca ekrana uyan bölümlerini kırpmasını etkinleştirin. Okunabilir/Yazılabilir Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Sunumun birden fazla kullanıcı arasında paylaşılıp paylaşılmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Bir sunum belgesindeki toplam slayt sayısını alır. Salt-okunur Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Bir sunumun konusunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Bir sunumun başlığını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Her belge bölümünün başlığını belirtir. Bu bölümler belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Salt-okunur string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Bir sunumun toplam düzenleme süresi. Okunabilir/Yazılabilir TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını alır. Salt-okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Tüm yerleşik özelliklerin varsayılan değerlerini temizler ve ayarlar. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Mevcut nesneyi kopyalar. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Mevcut nesneyi kopyalar. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Belirtilen indeksteki özel özelliğin adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden adlandırılmış bir boolean değer alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden adlandırılmış bir double değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden adlandırılmış bir float değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden adlandırılmış bir integer değeri alır. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden adlandırılmış bir string değeri alır. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Özel belge özelliklerinden duyarlılık etiketlerinin bir dizisini alır (Microsoft Information Protection SDK Metaverisi). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Adlandırılmış bir boolean özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Adlandırılmış bir DateTime özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Adlandırılmış bir double özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Adlandırılmış bir float özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Adlandırılmış bir integer özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Adlandırılmış bir string özel özelliğini ayarlar. |

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumu'nun yerleşik Özelliklerine nasıl erişileceğini gösterir.

```csharp
[C#]
// Sunumu temsil eden Presentation sınıfının bir örneğini oluşturur
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluşturur
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Yerleşik özellikleri görüntüler
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
// Sunumu temsil eden Presentation sınıfının bir örneğini oluşturur
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

### Bakınız

* arayüz [IDocumentProperties](../idocumentproperties)
* arayüz [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->