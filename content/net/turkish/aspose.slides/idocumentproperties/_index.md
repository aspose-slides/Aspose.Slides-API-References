---
title: IDocumentProperties
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
weight: 5690
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Bir uygulamanın şablonunu getirir veya ayarlar. Okuma/yazma String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Uygulama sürümünü getirir. Sadece okuma String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Sunumun yazarını getirir veya ayarlar. Okuma/yazma String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Sunumun kategorisini getirir veya ayarlar. Okuma/yazma String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Sunumun yorumlarını getirir veya ayarlar. Okuma/yazma String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Şirket özelliğini getirir veya ayarlar. Okuma/yazma String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Sunumun içerik durumunu getirir veya ayarlar. Okuma/yazma String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Sunumun içerik türünü getirir veya ayarlar. Okuma/yazma String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Bir koleksiyonda gerçekten bulunan özel özelliklerin sayısını getirir. Sadece okuma Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Bir sunumun oluşturulduğu tarihi getirir. Değerler UTC olarak verilmiştir. Okuma/yazma DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Belge bölümlerinin gruplandırmasını ve her gruptaki bölüm sayısını gösterir. Sadece okuma IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Bir sunum belgesindeki gizli slaytların sayısını belirtir. Sadece okuma Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | HyperlinkBase belge özelliğini getirir veya ayarlar. Okuma/yazma String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Bu belgeyi bir sonraki üretici açtığında, bağlantı ilişkileri bu bölümde belirtilen yeni bağlantılarla güncellenecektir. Okuma/yazma Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Belirtilen adla ilişkili özel özelliği getirir veya ayarlar. Okuma/yazma Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Sunumun anahtar kelimelerini getirir veya ayarlar. Okuma/yazma String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Sunumun en son yazdırıldığı tarihi getirir. Okuma/yazma DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Sunumu son değiştiren kişinin adını getirir veya ayarlar. Okuma/yazma String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Bir sunumun en son ne zaman değiştirildiğini getirir. Değerler UTC'dir. Presentation.DocumentProperties durumunda sadece okuma (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) yöntemiyle dönen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) yöntem özetindeki örneğe bakın. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Bir belgedeki bağlantıların güncel olup olmadığını gösterir. Bağlantıların güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Bağlantıların eski olduğunu belirtmek için bu öğeyi **false** olarak ayarlayın. Okuma/yazma Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Yönetici özelliğini getirir veya ayarlar. Okuma/yazma String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir. Sadece okuma Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Uygulamanın adını getirir veya ayarlar. Okuma/yazma String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Not içeren slaytların sayısını belirtir. Sadece okuma Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Uygulanabilir ise belgede bulunan paragraf sayısını belirtir. Sadece okuma Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Sunumun amaçlanan formatını getirir veya ayarlar. Okuma/yazma String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Sunum revizyon numarasını getirir veya ayarlar. Okuma/yazma Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Belge küçük resminin görüntüleme modunu gösterir. Küçük resmin ekrana ölçeklenmesini etkinleştirmek için bu öğeyi **true** olarak ayarlayın. Küçük resmin yalnızca ekrana uyan bölümlerini göstermek için kırpılmasını etkinleştirmek için bu öğeyi **false** olarak ayarlayın. Okuma/yazma Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okuma/yazma Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Sunum belgesindeki toplam slayt sayısını belirtir. Sadece okuma Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Sunum konusunu getirir veya ayarlar. Okuma/yazma String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Sunum başlığını getirir veya ayarlar. Okuma/yazma String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Her belge bölümünün başlığını belirtir. Bu bölümler belge bölümü değil, belge bölümlerinin kavramsal temsilleridir. Sadece okuma string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Bir sunumun toplam düzenleme süresi. Okuma/yazma TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Bir belgede bulunan toplam kelime sayısını belirtir. Sadece okuma Int32. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Tüm yerleşik özellikler için varsayılan değerleri temizler ve ayarlar. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Tüm özel özellikleri kaldırır. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Belirtilen isimle bir özel özelliğin varlığını kontrol eder. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Belirtilen indeksteki özel özellik adını döndürür. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Özel özelliklerden isimli bir Boolean değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Özel özelliklerden isimli bir DateTime değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Özel özelliklerden isimli bir double değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Özel özelliklerden isimli bir float değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Özel özelliklerden isimli bir integer değerini alır. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Özel özelliklerden isimli bir string değerini alır. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Belirtilen isimle ilişkili bir özel özelliği kaldırır. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | İsimli bir Boolean özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | İsimli bir DateTime özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | İsimli bir double özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | İsimli bir float özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | İsimli bir integer özel özelliği ayarlar. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | İsimli bir string özel özelliği ayarlar. |

### Bakınız

* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->