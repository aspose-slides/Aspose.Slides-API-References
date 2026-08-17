---
title: DocumentProperties
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/documentproperties/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Bir sunumun özelliklerini temsil eder.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Sunumu temsil eden Presentation sınıfını örnekleyin
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluşturun
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Yerleşik özellikleri görüntüle
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Presentation'ı temsil eden Presentation sınıfını örnekleyin
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Presentation ile ilişkili IDocumentProperties nesnesine bir referans oluşturun
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Yerleşik özellikleri ayarla
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Sunumunuzu bir dosyaya kaydedin
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Yeni bir [DocumentProperties](../../com.aspose.slides/documentproperties) sınıfı örneği başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Uygulama sürümünü döndürür. |
| [getNameOfApplication()](#getNameOfApplication--) | Uygulamanın adını döndürür veya ayarlar. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Uygulamanın adını döndürür veya ayarlar. |
| [getCompany()](#getCompany--) | Şirket özelliğini döndürür veya ayarlar. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Şirket özelliğini döndürür veya ayarlar. |
| [getManager()](#getManager--) | Yönetici özelliğini döndürür veya ayarlar. |
| [setManager(String value)](#setManager-java.lang.String-) | Yönetici özelliğini döndürür veya ayarlar. |
| [getPresentationFormat()](#getPresentationFormat--) | Bir sunumun amaçlanan biçimini döndürür veya ayarlar. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Bir sunumun amaçlanan biçimini döndürür veya ayarlar. |
| [getSharedDoc()](#getSharedDoc--) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Bir uygulamanın şablonunu döndürür veya ayarlar. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Bir uygulamanın şablonunu döndürür veya ayarlar. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Bir sunumun toplam düzenleme süresi. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Bir sunumun toplam düzenleme süresi. |
| [getTitle()](#getTitle--) | Bir sunumun başlığını döndürür veya ayarlar. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Bir sunumun başlığını döndürür veya ayarlar. |
| [getSubject()](#getSubject--) | Bir sunumun konusunu döndürür veya ayarlar. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Bir sunumun konusunu döndürür veya ayarlar. |
| [getAuthor()](#getAuthor--) | Bir sunumun yazarını döndürür veya ayarlar. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Bir sunumun yazarını döndürür veya ayarlar. |
| [getKeywords()](#getKeywords--) | Bir sunumun anahtar kelimelerini döndürür veya ayarlar. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Bir sunumun anahtar kelimelerini döndürür veya ayarlar. |
| [getComments()](#getComments--) | Bir sunumun yorumlarını döndürür veya ayarlar. |
| [setComments(String value)](#setComments-java.lang.String-) | Bir sunumun yorumlarını döndürür veya ayarlar. |
| [getCategory()](#getCategory--) | Bir sunumun kategorisini döndürür veya ayarlar. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Bir sunumun kategorisini döndürür veya ayarlar. |
| [getCreatedTime()](#getCreatedTime--) | Bir sunumun oluşturulduğu tarihi döndürür. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Bir sunumun oluşturulduğu tarihi döndürür. |
| [getLastSavedTime()](#getLastSavedTime--) | Bir sunumun son değiştirilme tarihini döndürür. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Bir sunumun son değiştirilme tarihini döndürür. |
| [getLastPrinted()](#getLastPrinted--) | Bir sunumun en son basıldığı tarihini döndürür. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Bir sunumun en son basıldığı tarihini döndürür. |
| [getLastSavedBy()](#getLastSavedBy--) | Sunumu son değiştiren kişinin adını döndürür veya ayarlar. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Sunumu son değiştiren kişinin adını döndürür veya ayarlar. |
| [getRevisionNumber()](#getRevisionNumber--) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [getContentStatus()](#getContentStatus--) | Bir sunumun içerik durumunu döndürür veya ayarlar. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Bir sunumun içerik durumunu döndürür veya ayarlar. |
| [getContentType()](#getContentType--) | Bir sunumun içerik türünü döndürür veya ayarlar. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Bir sunumun içerik türünü döndürür veya ayarlar. |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Bir koleksiyonda gerçekte bulunan özel özelliklerin sayısını döndürür. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Belirtilen indeksteki özel özellik adını döndürür. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Belirtilen isimle ilişkili özel özelliği kaldırır. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Belirtilen isimle ilişkili bir özel özelliğin varlığını kontrol eder. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Belirtilen isimle ilişkili özel özelliği döndürür veya ayarlar. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen isimle ilişkili özel özelliği döndürür veya ayarlar. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Özelleştirilmiş özelliklerden adlandırılmış bir boolean değerini alır. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Özelleştirilmiş özelliklerden adlandırılmış bir integer değerini alır. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Özelleştirilmiş özelliklerden adlandırılmış bir DateTime değerini alır. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Özelleştirilmiş özelliklerden adlandırılmış bir string değerini alır. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Özelleştirilmiş özelliklerden adlandırılmış bir float değerini alır. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Özelleştirilmiş özelliklerden adlandırılmış bir double değerini alır. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Adlandırılmış bir integer özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Adlandırılmış bir string özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Adlandırılmış bir float özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Adlandırılmış bir double özel özelliği ayarlar. |
| [clearCustomProperties()](#clearCustomProperties--) | Tüm özel özellikleri kaldırır. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Özelleştirilmiş belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Tüm yerleşik özellikler için varsayılan değerleri temizler ve ayarlar. |
| [getScaleCrop()](#getScaleCrop--) | Belge küçük resminin görüntüleme modunu gösterir. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Belge küçük resminin görüntüleme modunu gösterir. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Bir belgedeki bağlantıların güncel olup olmadığını gösterir. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Bir belgedeki bağlantıların güncel olup olmadığını gösterir. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [getSlides()](#getSlides--) | Bir sunum belgesindeki toplam slayt sayısını döndürür. |
| [getHiddenSlides()](#getHiddenSlides--) | Bir sunum belgesindeki gizli slayt sayısını döndürür. |
| [getNotes()](#getNotes--) | Not içeren bir sunumdaki slayt sayısını döndürür. |
| [getParagraphs()](#getParagraphs--) | Uygun ise bir belgede bulunan toplam paragraf sayısını döndürür. |
| [getWords()](#getWords--) | Bir belgede bulunan toplam kelime sayısını döndürür. |
| [getMultimediaClips()](#getMultimediaClips--) | Belgede bulunan ses veya video kliplerinin toplam sayısını döndürür. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Her belge kısmının başlığını belirtir. |
| [getHeadingPairs()](#getHeadingPairs--) | Belge bölümlerinin gruplandırılmasını ve her grup içindeki bölüm sayısını gösterir. |
| [deepClone()](#deepClone--) | Mevcut nesneyi kopyalar |
| [cloneT()](#cloneT--) | Mevcut nesneyi kopyalar |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Yeni bir [DocumentProperties](../../com.aspose.slides/documentproperties) sınıfı örneği başlatır.

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Uygulama sürümünü döndürür. Salt okunur String.

**Döndürür:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Uygulamanın adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Uygulamanın adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCompany() {#getCompany--}
```
public final String getCompany()
```

Şirket özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Şirket özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public final String getManager()
```

Yönetici özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Yönetici özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Bir sunumun amaçlanan biçimini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Bir sunumun amaçlanan biçimini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunabilir/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Bir uygulamanın şablonunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Bir uygulamanın şablonunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Bir sunumun toplam düzenleme süresi. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Bir sunumun toplam düzenleme süresi. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getTitle() {#getTitle--}
```
public final String getTitle()
```

Bir sunumun başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Bir sunumun başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```

Bir sunumun konusunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Bir sunumun konusunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Bir sunumun yazarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Bir sunumun yazarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Bir sunumun anahtar kelimelerini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Bir sunumun anahtar kelimelerini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```

Bir sunumun yorumlarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Bir sunumun yorumlarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```

Bir sunumun kategorisini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Bir sunumun kategorisini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date.

**Döndürür:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Returns the date a presentation was created. Values are in UTC. Read/write java.util.Date.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) Please see the example in [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) method summary.

**Döndürür:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Returns the date a presentation was last modified. Values are in UTC. Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). Can be changed via DocumentProperties instance returning by method [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) Please see the example in [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) method summary.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Returns the date when a presentation was printed last time. Read/write java.util.Date.

**Döndürür:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Returns the date when a presentation was printed last time. Read/write java.util.Date.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Returns or sets the name of a last person who modified a presentation. Read/write String.

**Döndürür:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Returns or sets the name of a last person who modified a presentation. Read/write String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Returns or sets the presentation revision number. Read/write int.

**Döndürür:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Returns or sets the presentation revision number. Read/write int.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Returns or sets the content status of a presentation. Read/write String.

**Döndürür:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Returns or sets the content status of a presentation. Read/write String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Returns or sets the content type of a presentation. Read/write String.

**Döndürür:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Returns or sets the content type of a presentation. Read/write String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


Returns or sets the HyperlinkBase document property. Read/write String.

**Döndürür:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


Returns or sets the HyperlinkBase document property. Read/write String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Returns the number of custom properties actually contained in a collection. Read-only int.

**Döndürür:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Return a custom property name at the specified index.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Alınacak özel özelliğin sıfırdan başlayan indeksi. |

**Döndürür:**
java.lang.String - Belirtilen dizindeki özel özellik adı.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Remove a custom property associated with a specified name.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özel özelliğin adı. |

**Döndürür:**
boolean - Özellik kaldırıldıysa true, aksi takdirde false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Check presents of a custom property with a specified name.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kontrol edilecek özel özelliğin adı. |

**Döndürür:**
boolean - Özellik mevcutsa true, aksi takdirde false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Returns or sets the custom property associated with a specified name. Read/write Object.

--------------------

Değer **int**, **float**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Döndürür:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Returns or sets the custom property associated with a specified name. Read/write Object.

--------------------

Değer **int**, **float**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Gets a named boolean value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | boolean[] | Özel özellik değeri |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Gets a named integer value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | int[] | Özel özellik değeri |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Gets a named DateTime value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.util.Date[] | Özel özellik değeri |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Gets a named string value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.lang.String[] | Özel özellik değeri |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Gets a named float value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | float[] | Özel özellik değeri |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Gets a named double value from the custom properties.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı. |
| value | double[] | Özel özellik değeri |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Sets a named boolean custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | boolean | Özel özellik değeri |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Sets a named integer custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | int | Özel özellik değeri |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Sets a named DateTime custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.util.Date | Özel özellik değeri |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Sets a named string custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.lang.String | Özel özellik değeri |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Sets a named float custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | float | Özel özellik değeri |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Sets a named double custom property.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | double | Özel özellik değeri |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Removes all custom properties.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


Gets an array of sensitivity labels from the custom document properties (Microsoft Information Protection SDK Metadata).

--------------------

> ``` 
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Özel belge özelliklerinden duyarlılık etiketlerini alın
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Etiketi koleksiyona ekle
>          // Burada etiket bilgilerinin geçerliliğini kontrol ekleyebilirsiniz (etiket mevcut vb.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```


Clears and sets default values for all builtIn properties.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Read/write boolean.

**Döndürür:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


Indicates the display mode of the document thumbnail. Set this element to **true** to enable scaling of the document thumbnail to the display. Set this element to **false** to enable cropping of the document thumbnail to show only sections that fits the display. Read/write boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


Indicates whether hyperlinks in a document are up-to-date. Set this element to **true** to indicate that hyperlinks are updated. Set this element to **false** to indicate that hyperlinks are outdated. Read/write boolean.

**Döndürür:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Bir belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlayarak köprülerin güncel olduğunu gösterir. Bu öğeyi **false** olarak ayarlayarak köprülerin eski olduğunu gösterir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Bu bölümde bir üretici tarafından yalnızca bu bölümde bir veya daha fazla köprünün güncellendiğini belirtir. Bu belgeyi açacak bir sonraki üretici, bu bölümde belirtilen yeni köprülerle köprü ilişkilerini güncelleyecektir. Okunur/Yazılabilir boolean.

**Dönüş:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Bu bölümde bir üretici tarafından yalnızca bu bölümde bir veya daha fazla köprünün güncellendiğini belirtir. Bu belgeyi açacak bir sonraki üretici, bu bölümde belirtilen yeni köprülerle köprü ilişkilerini güncelleyecektir. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Bir sunum belgesindeki toplam slayt sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Bir sunum belgesindeki gizli slayt sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Not içeren slaytların sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Uygulanabiliyorsa, bir belgede bulunan toplam paragraf sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Bir belgede bulunan toplam kelime sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Belgede bulunan ses veya video kliplerinin toplam sayısını döndürür. Salt okunur int.

**Dönüş:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Her belge bölümünün başlığını belirtir. Bu bölümler belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Salt okunur String[].

**Dönüş:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Salt okunur IHeadingPair[].

**Dönüş:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Mevcut nesneyi kopyalar

**Dönüş:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Mevcut nesneyi kopyalar

**Dönüş:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone