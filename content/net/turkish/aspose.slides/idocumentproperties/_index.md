---
title: IDocumentProperties
second_title: Aspose.Sildes for .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 5710
url: /tr/aspose.slides/idocumentproperties/
---
## IDocumentProperties arayüzü

Bir sunumun özelliklerini temsil eder.

```csharp
public interface IDocumentProperties
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Bir uygulamanın şablonunu alır veya ayarlar. Okunur/Yazılır String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Uygulama sürümünü döndürür. Sadece Okunur String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Bir sunumun yazarını alır veya ayarlar. Okunur/Yazılır String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Bir sunumun kategorisini alır veya ayarlar. Okunur/Yazılır String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Bir sunumun yorumlarını alır veya ayarlar. Okunur/Yazılır String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Şirket özelliğini alır veya ayarlar. Okunur/Yazılır String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Bir sunumun içerik durumunu alır veya ayarlar. Okunur/Yazılır String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Bir sunumun içerik türünü alır veya ayarlar. Okunur/Yazılır String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Bir koleksiyonda gerçekte bulunan özel özelliklerin sayısını döndürür. Sadece Okunur Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dedir. Okunur/Yazılır DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Sadece Okunur IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Bir sunum belgesindeki gizli slaytların sayısını belirtir. Sadece Okunur Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini alır veya ayarlar. Okunur/Yazılır String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Bu belgeyi bir sonraki üretici açtığında, köprü ilişkileri bu bölümde belirtilen yeni köprülerle güncellenecektir. Okunur/Yazılır Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Belirtilen adla ilişkili özel özelliği alır veya ayarlar. Okunur/Yazılır Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Bir sunumun anahtar kelimelerini alır veya ayarlar. Okunur/Yazılır String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Bir sunumun en son ne zaman yazdırıldığını döndürür. Okunur/Yazılır DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Bir sunumu son değiştiren kişinin adını alır veya ayarlar. Okunur/Yazılır String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Bir sunumun en son ne zaman değiştirildiğini döndürür. Değerler UTC'dedir. Presentation.DocumentProperties durumunda sadece okunur (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemiyle dönen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntem özetindeki örneğe bakın. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Bir belgedeki köprülerin güncel olup olmadığını gösterir. Köprülerin güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Köprülerin eski olduğunu belirtmek için bu öğeyi **false** olarak ayarlayın. Okunur/Yazılır Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Yönetici özelliğini alır veya ayarlar. Okunur/Yazılır String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir. Sadece Okunur Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Uygulamanın adını alır veya ayarlar. Okunur/Yazılır String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Notları içeren bir sunumdaki slayt sayısını belirtir. Sadece Okunur Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Uygun olduğunda bir belgede bulunan paragraf sayısını belirtir. Sadece Okunur Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Bir sunumun amaçlanan biçimini alır veya ayarlar. Okunur/Yazılır String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını alır veya ayarlar. Okunur/Yazılır Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Belge küçük resminin görüntüleme modunu gösterir. Belge küçük resminin ekrana ölçeklenmesini etkinleştirmek için bu öğeyi **true** olarak ayarlayın. Belge küçük resminin sadece ekrana uyan bölümleri gösterecek şekilde kırpılmasını etkinleştirmek için bu öğeyi **false** olarak ayarlayın. Okunur/Yazılır Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunur/Yazılır Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Bir sunum belgesindeki toplam slayt sayısını belirtir. Sadece Okunur Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Bir sunumun konusunu alır veya ayarlar. Okunur/Yazılır String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Bir sunumun başlığını alır veya ayarlar. Okunur/Yazılır String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Her belge bölümünün başlığını belirtir. Bu bölümler belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Sadece Okunur string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Bir sunumun toplam düzenleme süresi. Okunur/Yazılır TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını belirtir. Sadece Okunur Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Tüm yerleşik özelliklerin varsayılan değerlerini temizler ve ayarlar. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Belirtilen dizindeki bir özel özelliğin adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden adlandırılmış bir Boolean değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden adlandırılmış bir DateTime değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden adlandırılmış bir double değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden adlandırılmış bir float değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden adlandırılmış bir integer değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden adlandırılmış bir string değerini alır. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Adlandırılmış bir Boolean özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Adlandırılmış bir DateTime özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Adlandırılmış bir double özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Adlandırılmış bir float özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Adlandırılmış bir integer özel özelliğini ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Adlandırılmış bir string özel özelliğini ayarlar. |

### Ayrıca Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->