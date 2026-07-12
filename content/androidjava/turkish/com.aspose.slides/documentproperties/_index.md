---
title: DocumentProperties
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir sunumun özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/documentproperties/
---
**Kalıtım:**  
java.lang.Object

**Tüm Uygulanan Arabirimler:**  
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
>      // Yerleşik özellikleri göster
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
>      documentProperties.setAuthor("Aspose.Slides for Android via Java");
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
| [DocumentProperties()](#DocumentProperties--) | [DocumentProperties](../../com.aspose.slides/documentproperties) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
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
| [getSharedDoc()](#getSharedDoc--) | Sunumun birden çok kişi arasında paylaşılıp paylaşılamadığını belirler. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Sunumun birden çok kişi arasında paylaşılıp paylaşılamadığını belirler. |
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
| [getCreatedTime()](#getCreatedTime--) | Bir sunumun oluşturulduğu tarihi döndürür. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Bir sunumun oluşturulduğu tarihi döndürür. |
| [getLastSavedTime()](#getLastSavedTime--) | Bir sunumun son kez değiştirildiği tarihi döndürür. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Bir sunumun son kez değiştirildiği tarihi döndürür. |
| [getLastPrinted()](#getLastPrinted--) | Bir sunumun en son yazdırıldığı tarihi döndürür. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Bir sunumun en son yazdırıldığı tarihi döndürür. |
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
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Bir koleksiyonda gerçekten bulunan özel özelliklerin sayısını döndürür. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Belirtilen indeksteki özel özellik adını döndürür. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Belirtilen adla ilişkili bir özel özelliği kaldırır. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Belirtilen ada sahip bir özel özelliğin mevcut olup olmadığını denetler. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Adlandırılmış bir boolean özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Adlandırılmış bir tam sayı (integer) özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Adlandırılmış bir DateTime özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Adlandırılmış bir string özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Adlandırılmış bir float özel özelliği ayarlar. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Adlandırılmış bir double özel özelliği ayarlar. |
| [clearCustomProperties()](#clearCustomProperties--) | Tüm özel özellikleri kaldırır. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Özel belge özelliklerinden duyarlılık etiketlerinin bir dizisini alır (Microsoft Information Protection SDK Metadata). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Tüm yerleşik özellikleri temizler ve varsayılan değerlerini ayarlar. |
| [getScaleCrop()](#getScaleCrop--) | Belge küçük resminin görüntüleme modunu gösterir. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Belge küçük resminin görüntüleme modunu gösterir. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Bir belge içindeki bağlantıların güncel olup olmadığını gösterir. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Bir belge içindeki bağlantıların güncel olup olmadığını gösterir. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. |
| [getSlides()](#getSlides--) | Bir sunum belgesindeki toplam slayt sayısını döndürür. |
| [getHiddenSlides()](#getHiddenSlides--) | Bir sunum belgesindeki gizli slayt sayısını döndürür. |
| [getNotes()](#getNotes--) | Not içeren bir sunumdaki slayt sayısını döndürür. |
| [getParagraphs()](#getParagraphs--) | Bir belgede bulunan toplam paragraf sayısını döndürür (uygunsa). |
| [getWords()](#getWords--) | Bir belgede bulunan toplam kelime sayısını döndürür. |
| [getMultimediaClips()](#getMultimediaClips--) | Belgede bulunan toplam ses veya video klip sayısını döndürür. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Her belge parçasının başlığını belirtir. |
| [getHeadingPairs()](#getHeadingPairs--) | Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir. |
| [deepClone()](#deepClone--) | Mevcut nesneyi klonlar. |
| [cloneT()](#cloneT--) | Mevcut nesneyi klonlar. |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```


[DocumentProperties](../../com.aspose.slides/documentproperties) sınıfının yeni bir örneğini başlatır.

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


Bir sunumun hedef formatını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Bir sunumun hedef formatını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Sunumun birden çok kişi arasında paylaşılıp paylaşılamadığını belirler. Okunabilir/Yazılabilir boolean.

**Döndürür:**  
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Sunumun birden çok kişi arasında paylaşılıp paylaşılamadığını belirler. Okunabilir/Yazılabilir boolean.

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


Sunumun başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Sunumun başlığını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Sunumun konusunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sunumun konusunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Sunumun yazarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Sunumun yazarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Sunumun anahtar kelimelerini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Sunumun anahtar kelimelerini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public final String getComments()
```


Sunumun yorumlarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Sunumun yorumlarını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCategory() {#getCategory--}
```
public final String getCategory()
```


Sunumun kategorisini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Sunumun kategorisini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC’dedir. Okunabilir/Yazılabilir java.util.Date.

**Döndürür:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Bir sunumun oluşturulduğu tarihi döndürür. Değerler UTC’dedir. Okunabilir/Yazılabilir java.util.Date.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```


Bir sunumun son kez değiştirildiği tarihi döndürür. Değerler UTC’dedir. Salt okunur java.util.Date. Presentation.DocumentProperties durumunda salt okunurdur (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) yöntemiyle dönen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) yöntem özetindeki örneğe bakın.

**Döndürür:**  
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```


Bir sunumun son kez değiştirildiği tarihi döndürür. Değerler UTC’dedir. Salt okunur java.util.Date. Presentation.DocumentProperties durumunda salt okunurdur (çünkü IPresentation nesnesi kaydedilirken dahili olarak güncellenir). [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties) yöntemiyle dönen DocumentProperties örneği üzerinden değiştirilebilir. Lütfen [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-) yöntem özetindeki örneğe bakın.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```


Bir sunumun en son yazdırıldığı tarihi döndürür. Okunabilir/Yazılabilir java.util.Date.

**Döndürür:**  
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```


Bir sunumun en son yazdırıldığı tarihi döndürür. Okunabilir/Yazılabilir java.util.Date.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |
### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```


Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```


Sunumu en son değiştiren kişinin adını döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```


Sunum revizyon numarasını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Döndürür:**  
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```


Sunum revizyon numarasını döndürür veya ayarlar. Okunabilir/Yazılabilir int.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```


Sunumun içerik durumunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```


Sunumun içerik durumunu döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Sunumun içerik tipini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Sunumun içerik tipini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```


HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Döndürür:**  
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```


HyperlinkBase belge özelliğini döndürür veya ayarlar. Okunabilir/Yazılabilir String.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```


Koleksiyonda gerçekten bulunan özel özelliklerin sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```


Belirtilen indeksteki özel özellik adını döndürür.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak özel özelliğin sıfır tabanlı indeksi. |

**Döndürür:**  
java.lang.String - Belirtilen indeksteki özel özellik adı.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```


Belirtilen adla ilişkili bir özel özelliği kaldırır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Kaldırılacak özel özelliğin adı. |

**Döndürür:**  
boolean - Özellik kaldırıldıysa true, aksi halde false.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```


Belirtilen ada sahip bir özel özelliğin mevcut olup olmadığını denetler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Denenecek özel özelliğin adı. |

**Döndürür:**  
boolean - Özellik varsa true, yoksa false.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```


Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

--------------------

Değer **int**, **float**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |

**Döndürür:**  
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```


Belirtilen adla ilişkili özel özelliği döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

--------------------

Değer **int**, **float**, **String**, **boolean** veya **Date** olabilir.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |
### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```


Adlandırılmış bir boolean değer alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | boolean[] | Özel özellik değeri |
### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```


Adlandırılmış bir tam sayı değeri alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | int[] | Özel özellik değeri |
### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```


Adlandırılmış bir DateTime değeri alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.util.Date[] | Özel özellik değeri |
### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```


Adlandırılmış bir string değeri alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | java.lang.String[] | Özel özellik değeri |
### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```


Adlandırılmış bir float değeri alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı |
| value | float[] | Özel özellik değeri |
### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```


Adlandırılmış bir double değeri alır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Alınacak özel özelliğin adı. |
| value | double[] | Özel özellik değeri |
### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```


Adlandırılmış bir boolean özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | boolean | Özel özellik değeri |
### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```


Adlandırılmış bir tam sayı (integer) özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | int | Özel özellik değeri |
### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```


Adlandırılmış bir DateTime özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.util.Date | Özel özellik değeri |
### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```


Adlandırılmış bir string özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | java.lang.String | Özel özellik değeri |
### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```


Adlandırılmış bir float özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | float | Özel özellik değeri |
### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```


Adlandırılmış bir double özel özelliği ayarlar.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Ayarlanacak özel özelliğin adı |
| value | double | Özel özellik değeri |
### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```


Tüm özel özellikleri kaldırır.
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```


Özel belge özelliklerinden duyarlılık etiketlerinin bir dizisini alır (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Özel belge özelliklerinden duyarlılık etiketlerini al.
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Etiketi koleksiyona ekle.
>          // Burada etiket bilgisinin geçerliliğini (etiketin mevcut olması vb.) kontrol edebilirsiniz.
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


Tüm yerleşik özellikleri temizler ve varsayılan değerlerini ayarlar.
### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```


Belge küçük resminin görüntüleme modunu gösterir. Görüntüyü ölçeklemek için bu öğeyi **true** olarak ayarlayın. Küçük resmi kırpmak için **false** olarak ayarlayın. Okunabilir/Yazılabilir boolean.

**Döndürür:**  
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```


Belge küçük resminin görüntüleme modunu gösterir. Görüntüyü ölçeklemek için bu öğeyi **true** olarak ayarlayın. Küçük resmi kırpmak için **false** olarak ayarlayın. Okunabilir/Yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```


Bağlantıların güncel olup olmadığını gösterir. Bağlantıların güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Bağlantıların eski olduğunu belirtmek için **false** olarak ayarlayın. Okunabilir/Yazılabilir boolean.

**Döndürür:**  
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```


Bağlantıların güncel olup olmadığını gösterir. Bağlantıların güncel olduğunu belirtmek için bu öğeyi **true** olarak ayarlayın. Bağlantıların eski olduğunu belirtmek için **false** olarak ayarlayın. Okunabilir/Yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```


Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Sonraki üretici bu belgeyi açtığında, bu bölümde belirtilen yeni bağlantılarla ilişki güncellenecektir. Okunabilir/Yazılabilir boolean.

**Döndürür:**  
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public                  
```


Bu bölümde bir veya daha fazla bağlantının yalnızca bu bölümde bir üretici tarafından güncellendiğini belirtir. Sonraki üretici bu belgeyi açtığında, bu bölümde belirtilen yeni bağlantılarla ilişki güncellenecektir. Okunabilir/Yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getSlides() {#getSlides--}
```
public final int getSlides()
```


Bir sunum belgesindeki toplam slayt sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```


Bir sunum belgesindeki gizli slayt sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```


Not içeren bir sunumdaki slayt sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```


Bir belgede bulunan toplam paragraf sayısını döndürür (uygunsa). Salt okunur int.

**Döndürür:**  
int
### getWords() {#getWords--}
```
public final int getWords()
```


Bir belgede bulunan toplam kelime sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```


Belgede bulunan toplam ses veya video klip sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```


Her belge parçasının başlığını belirtir. Bu parçalar gerçek belge bölümleri değil, belge bölümlerinin kavramsal temsilleridir. Salt okunur String[].

**Döndürür:**  
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```


Belge parçalarının gruplandırılmasını ve her gruptaki parça sayısını gösterir. Salt okunur IHeadingPair[].

**Döndürür:**  
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut nesneyi klonlar

**Döndürür:**  
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```


Mevcut nesneyi klonlar

**Döndürür:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone