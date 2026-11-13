---
title: IDocumentProperties
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 5730
url: /tr/aspose.slides/idocumentproperties/
---
## IDocumentProperties arayüz

Bir sunumun özelliklerini temsil eder.

```csharp
public interface IDocumentProperties
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Bir uygulamanın şablonunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Uygulama sürümünü alır. Yalnızca okunabilir String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Sunumun yazarını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Sunumun kategorisini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Sunumun yorumlarını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Şirket özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Sunumun içerik durumunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Sunumun içerik türünü alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Bir koleksiyonda gerçekte bulunan özel özellik sayısını alır. Yalnızca okunabilir Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Sunumun oluşturulduğu tarihi alır. Değerler UTC zaman dilimindedir. Okunabilir/Yazılabilir DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Yalnızca okunabilir IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Sunum belgesindeki gizli slaytların sayısını belirtir. Yalnızca okunabilir Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Bu parçadaki bir veya daha fazla köprünün yalnızca bu parça içinde bir üretici tarafından güncellendiğini belirtir. Bu belgeyi bir sonraki üretici açtığında, bu parçada belirtilen yeni köprülerle köprü ilişkileri güncellenecektir. Okunabilir/Yazılabilir Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Belirtilen adla ilişkilendirilmiş özel özelliği alır veya ayarlar. Okunabilir/Yazılabilir Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Sunumun anahtar kelimelerini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Sunumun en son ne zaman yazdırıldığını alır. Okunabilir/Yazılabilir DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Sunumu son değiştiren kişinin adını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Sunumun en son değiştirildiği tarihi alır. Değerler UTC zaman dilimindedir. Presentation.DocumentProperties durumunda yalnızca okunabilir (çünkü IPresentation nesnesinin kaydetme sürecinde dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemi tarafından döndürülen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntemi özetindeki örneğe bakın. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlayın, böylece köprülerin güncel olduğunu gösterir. Bu öğeyi **false** olarak ayarlayın, böylece köprülerin güncel olmadığını gösterir. Okunabilir/Yazılabilir Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Yönetici özelliğini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Belgedeki ses veya video kliplerinin toplam sayısını belirtir. Yalnızca okunabilir Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Uygulamanın adını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Not içeren sunum slaytlarının sayısını belirtir. Yalnızca okunabilir Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Uygulanabilir olduğunda belgedeki toplam paragraf sayısını belirtir. Yalnızca okunabilir Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Sunumun amaçlanan biçimini alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını alır veya ayarlar. Okunabilir/Yazılabilir Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Belge minik resminin görüntüleme modunu belirtir. Bu öğeyi **true** olarak ayarlayın, böylece belge minik resmi ekrana ölçeklendirilir. Bu öğeyi **false** olarak ayarlayın, böylece belge minik resmi ekrana sığacak bölümlerle kırpılır. Okunabilir/Yazılabilir Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunabilir/Yazılabilir Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Sunum belgesindeki toplam slayt sayısını belirtir. Yalnızca okunabilir Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Sunumun konusunu alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Sunumun başlığını alır veya ayarlar. Okunabilir/Yazılabilir String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Her belge parçasının başlığını belirtir. Bu parçalar belge parçaları değil, belge bölümlerinin kavramsal temsilleridir. Yalnızca okunabilir string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Sunumun toplam düzenleme süresi. Okunabilir/Yazılabilir TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını belirtir. Yalnızca okunabilir Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Tüm yerleşik özellikler için varsayılan değerleri temizler ve ayarlar. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Belirtilen indeksteki özel özelliğin adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden adlandırılmış bir bool değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden adlandırılmış bir DateTime değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden adlandırılmış bir double değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden adlandırılmış bir float değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden adlandırılmış bir integer değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden adlandırılmış bir string değerini alır. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketleri dizisini alır. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Adlandırılmış bir bool özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Adlandırılmış bir DateTime özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Adlandırılmış bir double özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Adlandırılmış bir float özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Adlandırılmış bir integer özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Adlandırılmış bir string özel özelliğini ayarlar. |

### Ayrıca Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->