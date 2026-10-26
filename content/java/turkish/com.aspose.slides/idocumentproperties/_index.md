---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Bir sunumun özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Bir sunumun özelliklerini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Uygulama sürümünü döndürür. |
| [getNameOfApplication()](#getNameOfApplication--) | Uygulamanın adını döndürür veya ayarlar. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Uygulamanın adını döndürür veya ayarlar. |
| [getCompany()](#getCompany--) | Şirket özelliğini döndürür veya ayarlar. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Şirket özelliğini döndürür veya ayarlar. |
| [getManager()](#getManager--) | Yönetici özelliğini döndürür veya ayarlar. |
| [setManager(String value)](#setManager-java.lang.String-) | Yönetici özelliğini döndürür veya ayarlar. |
| [getPresentationFormat()](#getPresentationFormat--) | Sunumun amaçlanan formatını döndürür veya ayarlar. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Sunumun amaçlanan formatını döndürür veya ayarlar. |
| [getSharedDoc()](#getSharedDoc--) | Sunumun birden fazla kişi tarafından paylaşılıp paylaşılmadığını belirler. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Sunumun birden fazla kişi tarafından paylaşılıp paylaşılmadığını belirler. |
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
| [getLastSavedTime()](#getLastSavedTime--) | Bir sunumun son düzenlenme tarihini döndürür. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Bir sunumun son düzenlenme tarihini döndürür. |
| [getLastPrinted()](#getLastPrinted--) | Bir sunumun en son yazdırıldığı tarihi döndürür. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Bir sunumun en son yazdırıldığı tarihi döndürür. |
| [getLastSavedBy()](#getLastSavedBy--) | Bir sunumu en son değiştiren kişinin adını döndürür veya ayarlar. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Bir sunumu en son değiştiren kişinin adını döndürür veya ayarlar. |
| [getRevisionNumber()](#getRevisionNumber--) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [getContentStatus()](#getContentStatus--) | Sunumun içerik durumunu döndürür veya ayarlar. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Sunumun içerik durumunu döndürür veya ayarlar. |
| [getContentType()](#getContentType--) | Sunumun içerik türünü döndürür veya ayarlar. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sunumun içerik türünü döndürür veya ayarlar. |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [getScaleCrop()](#getScaleCrop--) | Belge küçük resminin görüntüleme kipini gösterir. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Belge küçük resminin görüntüleme kipini gösterir. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Belgedeki hiperlinklerin güncel olup olmadığını gösterir. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Belgedeki hiperlinklerin güncel olup olmadığını gösterir. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Bu bölümde bir veya daha fazla hiperlinkin yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Bu bölümde bir veya daha fazla hiperlinkin yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [getSlides()](#getSlides--) | Bir sunum belgesindeki toplam slayt sayısını belirtir. |
| [getHiddenSlides()](#getHiddenSlides--) | Bir sunum belgesindeki gizli slayt sayısını belirtir. |
| [getNotes()](#getNotes--) | Notlar içeren bir sunumdaki slayt sayısını belirtir. |
| [getParagraphs()](#getParagraphs--) | Uygun olduğunda bir belgede bulunan toplam paragraf sayısını belirtir. |
| [getWords()](#getWords--) | Bir belgede bulunan toplam kelime sayısını belirtir. |
| [getMultimediaClips()](#getMultimediaClips--) | Belgede mevcut olan ses veya video kliplerinin toplam sayısını belirtir. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Her belge parçasının başlığını belirtir. |
| [getHeadingPairs()](#getHeadingPairs--) | Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Bir koleksiyonda gerçekte bulunan özel özelliklerin sayısını döndürür. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Belirtilen dizinde bir özel özellik adını döndürür. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Belirtilen adla bir özel özelliğin varlığını kontrol eder. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. |
| [clearCustomProperties()](#clearCustomProperties--) | Tüm özel özellikleri kaldırır. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Tüm yerleşik özelliklerin değerlerini temizler ve varsayılanlara ayarlar. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Özel özelliklerden adlandırılmış bir boolean değer alır. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Özel özelliklerden adlandırılmış bir tam sayı değeri alır. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Özel özelliklerden adlandırılmış bir DateTime değeri alır. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Özel özelliklerden adlandırılmış bir metin değeri alır. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Özel özelliklerden adlandırılmış bir float değeri alır. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Özel özelliklerden adlandırılmış bir double değeri alır. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Adlandırılmış bir tam sayı özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Adlandırılmış bir metin özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Adlandırılmış bir float özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Adlandırılmış bir double özel özelliği ayarlar. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır. |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Uygulama sürümünü döndürür. Read-only String.

--------------------

Bu öğenin içeriği XX.YYYY biçiminde olmalıdır; burada X ve Y sayısal değerleri temsil eder; aksi takdirde belge uyumsuz kabul edilir. Aspose.Slides sürümünü XX.YY.ZZ biçiminde temsil eder, burada: XX - ana sürüm YY - alt sürüm ZZ - yama sürümü. Örneğin, 23.0105 değeri Aspose.Slides sürüm 23.1.5 anlamına gelir.

**Döndürür:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Uygulamanın adını döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Uygulamanın adını döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Şirket özelliğini döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Şirket özelliğini döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Yönetici özelliğini döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Yönetici özelliğini döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Sunumun amaçlanan formatını döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Sunumun amaçlanan formatını döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Sunumun birden fazla kişi tarafından paylaşılıp paylaşılmadığını belirler. Read/write boolean.

**Döndürür:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Sunumun birden fazla kişi tarafından paylaşılıp paylaşılmadığını belirler. Read/write boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Bir uygulamanın şablonunu döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Bir uygulamanın şablonunu döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Bir sunumun toplam düzenleme süresi. Read/write double.

**Döndürür:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Bir sunumun toplam düzenleme süresi. Read/write double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Sunumun başlığını döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Sunumun başlığını döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Sunumun konusunu döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Sunumun konusunu döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Sunumun yazarını döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Sunumun yazarını döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Sunumun anahtar kelimelerini döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Sunumun anahtar kelimelerini döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Sunumun yorumlarını döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Sunumun yorumlarını döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Sunumun kategorisini döndürür veya ayarlar. Read/write String.

**Döndürür:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Sunumun kategorisini döndürür veya ayarlar. Read/write String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
| değer | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dedir. Okunur/Yazılır java.util.Date.

**Döndürür:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC'dedir. Okunur/Yazılır java.util.Date.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Bir sunumun en son değiştirildiği tarihi döndürür. Değerler UTC'dedir. Presentation.DocumentProperties durumunda sadece okunur (çünkü IPresentation nesnesi kaydetme işlemi sırasında dahili olarak güncellenir). DocumentProperties örneği [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metodu aracılığıyla değiştirilebilir. [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metodunun özetindeki örneğe bakınız.

**Döndürür:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Bir sunumun en son değiştirildiği tarihi döndürür. Değerler UTC'dedir. Presentation.DocumentProperties durumunda sadece okunur (çünkü IPresentation nesnesi kaydetme işlemi sırasında dahili olarak güncellenir). DocumentProperties örneği [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) metodu aracılığıyla değiştirilebilir. [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) metodunun özetindeki örneğe bakınız.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Bir sunumun en son yazdırıldığı tarihi döndürür. Okunur/Yazılır java.util.Date.

**Döndürür:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Bir sunumun en son yazdırıldığı tarihi döndürür. Okunur/Yazılır java.util.Date.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Bir sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Bir sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Sunum revizyon numarasını döndürür veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Sunum revizyon numarasını döndürür veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Sunumun içerik durumunu döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Sunumun içerik durumunu döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Sunumun içerik tipini döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Sunumun içerik tipini döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Belge küçük resmi görüntüleme modunu gösterir. Bu öğeyi **true** olarak ayarlarsanız, küçük resim ekrana ölçeklendirilir. Bu öğeyi **false** olarak ayarlarsanız, küçük resim kırpılır ve yalnızca ekrana sığan bölümler gösterilir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Belge küçük resmi görüntüleme modunu gösterir. Bu öğeyi **true** olarak ayarlarsanız, küçük resim ekrana ölçeklendirilir. Bu öğeyi **false** olarak ayarlarsanız, küçük resim kırpılır ve yalnızca ekrana sığan bölümler gösterilir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Belgedeki bağlantıların güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız, bağlantıların güncel olduğunu belirtir. Bu öğeyi **false** olarak ayarlarsanız, bağlantıların güncel olmadığını belirtir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Belgedeki bağlantıların güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız, bağlantıların güncel olduğunu belirtir. Bu öğeyi **false** olarak ayarlarsanız, bağlantıların güncel olmadığını belirtir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Belgeyi bir sonraki üretici açtığında, bağlantı ilişkileri bu bölümde belirtilen yeni bağlantılarla güncellenecektir. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Belgeyi bir sonraki üretici açtığında, bağlantı ilişkileri bu bölümde belirtilen yeni bağlantılarla güncellenecektir. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Sunum belgesindeki toplam slayt sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Sunum belgesindeki gizli slayt sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Not içeren slaytların sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Belgede bulunabilecek toplam paragraf sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Belgede bulunan toplam kelime sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir. Sadece okunur int.

**Döndürür:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Her belge bölümünün başlığını belirtir. Bu bölümler gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilidir. Sadece okunur java.lang.String[].

**Döndürür:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Belge bölümlerinin gruplandırılmasını ve her gruptaki bölüm sayısını gösterir. Sadece okunur com.aspose.slides.IHeadingPair[].

**Döndürür:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Bir koleksiyonda gerçekte bulunan özel özellik sayısını döndürür. Sadece okunur int.

**Döndürür:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Belirtilen indekste bir özel özellik adını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak özel özelliğin sıfır tabanlı indeksi. |

**Döndürür:**
java.lang.String - Belirtilen indekste özel özellik adı.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Belirtilen isimle ilişkili bir özel özelliği kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özel özelliğin adı. |

**Döndürür:**
boolean - Özellik kaldırıldıysa true, aksi takdirde false.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Belirtilen isimde bir özel özelliğin varlığını denetler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Denetlenecek özel özelliğin adı. |

**Döndürür:**
boolean - Özellik mevcutsa true, aksi takdirde false.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Belirtilen isimle ilişkili özel özelliği döndürür veya ayarlar. Okunur/Yazılır Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Döndürür:**
java.lang.Object

Değer **int**, **float**, **double**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Döndürür:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Belirtilen isimle ilişkili özel özelliği döndürür veya ayarlar. Okunur/Yazılır Object.

Değer **int**, **float**, **double**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Tüm özel özellikleri kaldırır.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Tüm yerleşik özellikleri temizler ve varsayılan değerlerini ayarlar.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Özel özelliklerden adlandırılmış bir boolean değer alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | boolean[] | Özel özellik değeri |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Özel özelliklerden adlandırılmış bir integer değer alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | int[] | Özel özellik değeri |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Özel özelliklerden adlandırılmış bir DateTime değeri alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.util.Date[] | Özel özellik değeri |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Özel özelliklerden adlandırılmış bir string değeri alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.lang.String[] | Özel özellik değeri |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Özel özelliklerden adlandırılmış bir float değeri alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | float[] | Özel özellik değeri |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Özel özelliklerden adlandırılmış bir double değeri alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | double[] | Özel özellik değeri |
| ad | java.lang.String | Alınacak özel özelliğin adı. |
| değer | double[] | Özel özellik değeri |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Adlandırılmış bir boolean özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | boolean | Özel özellik değeri |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Adlandırılmış bir tam sayı özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | int | Özel özellik değeri |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Adlandırılmış bir DateTime özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.util.Date | Özel özellik değeri |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Adlandırılmış bir string özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.lang.String | Özel özellik değeri |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Adlandırılmış bir float özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | float | Özel özellik değeri |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Adlandırılmış bir double özel özelliği ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | double | Özel özellik değeri |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır.

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
com.aspose.slides.ISensitivityLabel[]