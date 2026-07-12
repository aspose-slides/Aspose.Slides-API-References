---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Sunumun özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Bir sunumun özelliklerini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Uygulama sürümünü döndürür. |
| [getNameOfApplication()](#getNameOfApplication--) | Uygulamanın adını döndürür veya ayarlar. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Uygulamanın adını döndürür veya ayarlar. |
| [getCompany()](#getCompany--) | Şirket özelliğini döndürür veya ayarlar. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Şirket özelliğini döndürür veya ayarlar. |
| [getManager()](#getManager--) | Yönetici özelliğini döndürür veya ayarlar. |
| [setManager(String value)](#setManager-java.lang.String-) | Yönetici özelliğini döndürür veya ayarlar. |
| [getPresentationFormat()](#getPresentationFormat--) | Bir sunumun hedef formatını döndürür veya ayarlar. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Bir sunumun hedef formatını döndürür veya ayarlar. |
| [getSharedDoc()](#getSharedDoc--) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Bir uygulamanın şablonunu döndürür veya ayarlar. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Bir uygulamanın şablonunu döndürür veya ayarlar. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Bir sunumun toplam düzenleme süresi. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Bir sunumun toplam düzenleme süresi. |
| [getTitle()](#getTitle--) | Sunumun başlığını döndürür veya ayarlar. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sunumun başlığını döndürür veya ayarlar. |
| [getSubject()](#getSubject--) | Sunumun konusunu döndürür veya ayarlar. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sunumun konusunu döndürür veya ayarlar. |
| [getAuthor()](#getAuthor--) | Sunumun yazarını döndürür veya ayarlar. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Sunumun yazarını döndürür veya ayarlar. |
| [getKeywords()](#getKeywords--) | Sunumun anahtar kelimelerini döndürür veya ayarlar. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Sunumun anahtar kelimelerini döndürür veya ayarlar. |
| [getComments()](#getComments--) | Sunumun yorumlarını döndürür veya ayarlar. |
| [setComments(String value)](#setComments-java.lang.String-) | Sunumun yorumlarını döndürür veya ayarlar. |
| [getCategory()](#getCategory--) | Sunumun kategorisini döndürür veya ayarlar. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Sunumun kategorisini döndürür veya ayarlar. |
| [getCreatedTime()](#getCreatedTime--) | Sunumun oluşturulduğu tarihi döndürür. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Sunumun oluşturulduğu tarihi döndürür. |
| [getLastSavedTime()](#getLastSavedTime--) | Sunumun en son değiştirildiği tarihi döndürür. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Sunumun en son değiştirildiği tarihi döndürür. |
| [getLastPrinted()](#getLastPrinted--) | Sunumun en son yazdırıldığı tarihi döndürür. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Sunumun en son yazdırıldığı tarihi döndürür. |
| [getLastSavedBy()](#getLastSavedBy--) | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. |
| [getRevisionNumber()](#getRevisionNumber--) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Sunum revizyon numarasını döndürür veya ayarlar. |
| [getContentStatus()](#getContentStatus--) | Sunumun içerik durumunu döndürür veya ayarlar. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Sunumun içerik durumunu döndürür veya ayarlar. |
| [getContentType()](#getContentType--) | Sunumun içerik tipini döndürür veya ayarlar. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Sunumun içerik tipini döndürür veya ayarlar. |
| [getHyperlinkBase()](#getHyperlinkBase--) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | HyperlinkBase belge özelliğini döndürür veya ayarlar. |
| [getScaleCrop()](#getScaleCrop--) | Belge küçük resminin görüntüleme modunu gösterir. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Belge küçük resminin görüntüleme modunu gösterir. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Belgedeki köprülerin güncel olup olmadığını gösterir. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Belgedeki köprülerin güncel olup olmadığını gösterir. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [getSlides()](#getSlides--) | Bir sunum belgesindeki toplam slayt sayısını belirtir. |
| [getHiddenSlides()](#getHiddenSlides--) | Bir sunum belgesindeki gizli slayt sayısını belirtir. |
| [getNotes()](#getNotes--) | Not içeren bir sunumdaki slayt sayısını belirtir. |
| [getParagraphs()](#getParagraphs--) | Belgede bulunan paragraf sayısını belirtir (uygulanabilir ise). |
| [getWords()](#getWords--) | Belgede bulunan toplam kelime sayısını belirtir. |
| [getMultimediaClips()](#getMultimediaClips--) | Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Her belge bölümünün başlığını belirtir. |
| [getHeadingPairs()](#getHeadingPairs--) | Belge bölümlerinin gruplandırılmasını ve her grup içindeki bölüm sayısını gösterir. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Bir koleksiyonda aslında bulunan özel özelliklerin sayısını döndürür. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Belirtilen indeksdeki özel özellik adını döndürür. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Belirtilen ada sahip bir özel özelliğin varlığını kontrol eder. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Belirtilen ada sahip özel özelliği döndürür veya ayarlar. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen ada sahip özel özelliği döndürür veya ayarlar. |
| [clearCustomProperties()](#clearCustomProperties--) | Tüm özel özellikleri kaldırır. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Tüm yerleşik özelliklerin varsayılan değerlerini temizler ve ayarlar. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Özel özelliklerden adlandırılmış bir boolean değeri alır. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Özel özelliklerden adlandırılmış bir integer (tam sayı) değeri alır. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Özel özelliklerden adlandırılmış bir DateTime değerini alır. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Özel özelliklerden adlandırılmış bir string değeri alır. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Özel özelliklerden adlandırılmış bir float değeri alır. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Özel özelliklerden adlandırılmış bir double değeri alır. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Adlandırılmış bir integer özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Adlandırılmış bir string özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Adlandırılmış bir float özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Adlandırılmış bir double özel özelliği ayarlar. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Özel belge özelliklerinden bir dizi hassasiyet etiketi alır (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```


Uygulama sürümünü döndürür. Salt-okunur String.

--------------------

Bu öğenin içeriği, X ve Y sayısal değerleri temsil eden XX.YYYY biçiminde olmalıdır; aksi takdirde belge uyumsuz kabul edilir. Aspose.Slides sürümünü XX.YY.ZZ biçiminde gösterir, burada: XX - ana sürüm YY - alt sürüm ZZ - yama sürümü. Örneğin, 23.0105 değeri Aspose.Slides sürüm 23.1.5 anlamına gelir.

**Returns:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```


Uygulamanın adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```


Uygulamanın adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```


Şirket özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```


Şirket özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```


Yönetici özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```


Yönetici özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```


Bir sunumun hedef formatını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```


Bir sunumun hedef formatını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```


Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunur/yazılabilir boolean.

**Returns:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```


Sunumun birden fazla kişi arasında paylaşılıp paylaşılmadığını belirler. Okunur/yazılabilir boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```


Bir uygulamanın şablonunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```


Bir uygulamanın şablonunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```


Bir sunumun toplam düzenleme süresi. Okunur/yazılabilir double.

**Returns:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```


Bir sunumun toplam düzenleme süresi. Okunur/yazılabilir double.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Sunumun başlığını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Sunumun başlığını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```


Sunumun konusunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```


Sunumun konusunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```


Sunumun yazarını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```


Sunumun yazarını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```


Sunumun anahtar kelimelerini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```


Sunumun anahtar kelimelerini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```


Sunumun yorumlarını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```


Sunumun yorumlarını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```


Sunumun kategorisini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```


Sunumun kategorisini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Sunumun oluşturulduğu tarihi döndürür. Değerler UTC olarak verilir. Okunur/yazılabilir java.util.Date.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Sunumun oluşturulduğu tarihi döndürür. Değerler UTC olarak verilir. Okunur/yazılabilir java.util.Date.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


Sunumun en son değiştirildiği tarihi döndürür. Değerler UTC olarak verilir. Presentation.DocumentProperties durumunda salt-okunur (çünkü IPresentation nesnesi kaydedilirken içsel olarak güncellenir). [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) yöntemi ile dönen DocumentProperties örneği aracılığıyla değiştirilebilir. Lütfen [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) yöntemi özetindeki örneğe bakın.

**Returns:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


Sunumun en son değiştirildiği tarihi döndürür. Değerler UTC olarak verilir. Presentation.DocumentProperties durumunda salt-okunur (çünkü IPresentation nesnesi kaydedilirken içsel olarak güncellenir). [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) yöntemi ile dönen DocumentProperties örneği aracılığıyla değiştirilebilir. Lütfen [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) yöntemi özetindeki örneğe bakın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


Sunumun en son yazdırıldığı tarihi döndürür. Okunur/yazılabilir java.util.Date.

**Returns:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


Sunumun en son yazdırıldığı tarihi döndürür. Okunur/yazılabilir java.util.Date.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


Sunum revizyon numarasını döndürür veya ayarlar. Okunur/yazılabilir int.

**Returns:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


Sunum revizyon numarasını döndürür veya ayarlar. Okunur/yazılabilir int.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


Sunumun içerik durumunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```


Sunumun içerik durumunu döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Sunumun içerik tipini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


Sunumun içerik tipini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Returns:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunur/yazılabilir String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


Belge küçük resminin görüntüleme modunu gösterir. Bu öğeyi **true** olarak ayarlarsanız belge küçük resminin ekrana ölçeklenmesi etkinleşir. Bu öğeyi **false** olarak ayarlarsanız belge küçük resminin kırpılması etkinleşir ve yalnızca ekrana uyan bölümler gösterilir. Okunur/yazılabilir boolean.

**Returns:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


Belge küçük resminin görüntüleme modunu gösterir. Bu öğeyi **true** olarak ayarlarsanız belge küçük resminin ekrana ölçeklenmesi etkinleşir. Bu öğeyi **false** olarak ayarlarsanız belge küçük resminin kırpılması etkinleşir ve yalnızca ekrana uyan bölümler gösterilir. Okunur/yazılabilir boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


Belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız köprülerin güncel olduğunu gösterir. Bu öğeyi **false** olarak ayarlarsanız köprülerin güncel olmadığını gösterir. Okunur/yazılabilir boolean.

**Returns:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


Belgedeki köprülerin güncel olup olmadığını gösterir. Bu öğeyi **true** olarak ayarlarsanız köprülerin güncel olduğunu gösterir. Bu öğeyi **false** olarak ayarlarsanız köprülerin güncel olmadığını gösterir. Okunur/yazılabilir boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Sonraki üretici bu belgeyi açtığında yeni köprülerle ilişkileri güncelleyecektir. Okunur/yazılabilir boolean.

**Returns:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


Bu bölümde bir veya daha fazla köprünün yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Sonraki üretici bu belgeyi açtığında yeni köprülerle ilişkileri güncelleyecektir. Okunur/yazılabilir boolean.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


Bir sunum belgesindeki toplam slayt sayısını belirtir. Salt-okunur int.

**Returns:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


Bir sunum belgesindeki gizli slayt sayısını belirtir. Salt-okunur int.

**Returns:**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


Not içeren bir sunumdaki slayt sayısını belirtir. Salt-okunur int.

**Returns:**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


Belgede bulunan paragraf sayısını belirtir (uygulanabilir ise). Salt-okunur int.

**Returns:**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```


Belgede bulunan toplam kelime sayısını belirtir. Salt-okunur int.

**Returns:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```


Belgede bulunan ses veya video kliplerinin toplam sayısını belirtir. Salt-okunur int.

**Returns:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```


Her belge bölümünün başlığını belirtir. Bu bölümler gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilidir. Salt-okunur String[].

**Returns:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


Belge bölümlerinin gruplandırılmasını ve her grup içindeki bölüm sayısını gösterir. Salt-okunur IHeadingPair[].

**Returns:**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


Bir koleksiyonda aslında bulunan özel özelliklerin sayısını döndürür. Salt-okunur int.

**Returns:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


Belirtilen indeksteki özel özellik adını döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak özel özelliğin sıfır tabanlı indeksi |

**Returns:**
java.lang.String - Belirtilen indeksteki özel özellik adı.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```


Belirtilen adla ilişkili bir özel özelliği kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özel özelliğin adı. |

**Returns:**
boolean - Bir özellik kaldırıldıysa true, aksi halde false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```


Belirtilen ada sahip bir özel özelliğin varlığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kontrol edilecek özel özelliğin adı. |

**Returns:**
boolean - Özellik mevcutsa true, aksi halde false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```


Belirtilen ada sahip özel özelliği döndürür veya ayarlar. Okunur/yazılabilir Object.

--------------------

Value can be **int**, **float**, **double**, **String**, **boolean** or **Date**.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```


Belirtilen ada sahip özel özelliği döndürür veya ayarlar. Okunur/yazılabilir Object.

--------------------

Value can be **int**, **float**, **double**, **String**, **boolean** or **Date**.

**Parameters:**
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


Tüm yerleşik özelliklerin varsayılan değerlerini temizler ve ayarlar.
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


Özel özelliklerden adlandırılmış bir boolean değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | boolean[] | Özel özellik değeri |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


Özel özelliklerden adlandırılmış bir integer (tam sayı) değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | int[] | Özel özellik değeri |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


Özel özelliklerden adlandırılmış bir DateTime değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.util.Date[] | Özel özellik değeri |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


Özel özelliklerden adlandırılmış bir string değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.lang.String[] | Özel özellik değeri |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


Özel özelliklerden adlandırılmış bir float değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | float[] | Özel özellik değeri |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


Özel özelliklerden adlandırılmış bir double değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı. |
| value | double[] | Özel özellik değeri |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```


Adlandırılmış bir boolean özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | boolean | Özel özellik değeri |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```


Adlandırılmış bir integer özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | int | Özel özellik değeri |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```


Adlandırılmış bir DateTime özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.util.Date | Özel özellik değeri |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```


Adlandırılmış bir string özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.lang.String | Özel özellik değeri |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```


Adlandırılmış bir float özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | float | Özel özellik değeri |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```


Adlandırılmış bir double özel özelliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | double | Özel özellik değeri |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```


Özel belge özelliklerinden bir dizi hassasiyet etiketi alır (Microsoft Information Protection SDK Metadata).

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

**Returns:**
com.aspose.slides.ISensitivityLabel[]