---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunum yüklenirken format veya varsayılan yazı tipi gibi ek seçenekleri belirlemenizi sağlar.
type: docs
url: /tr/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Bir sunum yüklenirken ek seçenekleri (örneğin format veya varsayılan yazı tipi) belirtmenizi sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Yüklemek için bir sunumun formatını alır veya ayarlar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Yüklemek için bir sunumun formatını alır veya ayarlar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılan Regular yazı tipini alır veya ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Regular yazı tipini alır veya ayarlar. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini alır veya ayarlar. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini alır veya ayarlar. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Kaynak yazı tipi bulunamadığında kullanılan Asian yazı tipini alır veya ayarlar. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Asian yazı tipini alır veya ayarlar. |
| [getPassword()](#getPassword--) | Şifreyi alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi alır veya ayarlar. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Sunum dosyası şifre korumalıysa bu özellik anlamlıdır. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Sunum dosyası şifre korumalıysa bu özellik anlamlıdır. |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Geçici dosyaların kullanılması veya bellekteki maksimum BLOB baytları gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Geçici dosyaların kullanılması veya bellekteki maksimum BLOB baytları gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Sunumda kullanılacak harici yazı tiplerinin kaynaklarını belirtir. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Sunumda kullanılacak harici yazı tiplerinin kaynaklarını belirtir. |
| [getInterruptionToken()](#getInterruptionToken--) | Kesinti isteklerini izlemek için kullanılan token. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Kesinti isteklerini izlemek için kullanılan token. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır veya ayarlar. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır veya ayarlar. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ek tablo davranışlarını belirlemek için kullanılabilecek seçenekleri temsil eder. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Ek tablo davranışlarını belirlemek için kullanılabilecek seçenekleri temsil eder. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides'in sunum yükleme sırasında tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides'in sunum yükleme sırasında tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Yüklemek için bir sunumun formatını alır veya ayarlar. Okuma/yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Yüklemek için bir sunumun formatını alır veya ayarlar. Okuma/yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Regular yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Regular yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Symbol yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Asian yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Asian yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Şifreyi alır veya ayarlar. Okuma-yazma String.

Değer: Şifre.

**Döndürür:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Şifreyi alır veya ayarlar. Okuma-yazma String.

Değer: Şifre.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Sunum dosyası şifre korumalıysa bu özellik anlamlıdır. **true** değeri, şifre yok sayılarak yalnızca belge özelliklerinin şifreli bir sunum dosyasından yükleneceği anlamına gelir. **false** değeri, doğru şifre kullanılarak tüm şifreli sunumun yükleneceği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri **true** ise belge özellikleri yüklenemez ve bir istisna fırlatılır. Okuma-yazma boolean.

**Döndürür:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Sunum dosyası şifre korumalıysa bu özellik anlamlıdır. **true** değeri, şifre yok sayılarak yalnızca belge özelliklerinin şifreli bir sunum dosyasından yükleneceği anlamına gelir. **false** değeri, doğru şifre kullanılarak tüm şifreli sunumun yükleneceği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri **true** ise belge özellikleri yüklenemez ve bir istisna fırlatılır. Okuma-yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okuma/yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Döndürür:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okuma/yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Geçici dosyaların kullanılması veya bellekteki maksimum BLOB baytları gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler, belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

Bir Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – örneğin BLOB bir ses, video veya sunum olabilir.

**Döndürür:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Geçici dosyaların kullanılması veya bellekteki maksimum BLOB baytları gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler, belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

Bir Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – örneğin BLOB bir ses, video veya sunum olabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Sunumda kullanılacak harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun yaşam süresi boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz.

**Döndürür:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Sunumda kullanılacak harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun yaşam süresi boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örneğinin ömür süresini yönetir. Sunum yükleme veya kaydetme gibi uzun süren bir işlem, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metodunun [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılır.

**Döndürür:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örneğinin ömür süresini yönetir. Sunum yükleme veya kaydetme gibi uzun süren bir işlem, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metodunun [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır veya ayarlar. Okuma/yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Döndürür:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Harici kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır veya ayarlar. Okuma/yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Ek tablo davranışlarını belirlemek için kullanılabilecek seçenekleri temsil eder.

**Döndürür:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Ek tablo davranışlarını belirlemek için kullanılabilecek seçenekleri temsil eder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Sunum metni için varsayılan dili alır veya ayarlar. Okuma/yazma String.

--------------------

> ```
> Example:
>   
>  // Yükleme seçeneklerini varsayılan metin kültürünü tanımlamak için kullan
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni bir dikdörtgen şekli ekle ve metin ekle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölümün dilini kontrol et
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Sunum metni için varsayılan dili alır veya ayarlar. Okuma/yazma String.

--------------------

> ```
> Example:
>   
>  // Yükleme seçeneklerini varsayılan metin kültürünü tanımlamak için kullan
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni dikdörtgen şekil ekleyip metin ekle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölümün dilini kontrol et
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Aspose.Slides'in sunum yükleme sırasında tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin türleri:

 *  
 *  
 *  

Okuma/yazma  boolean .

--------------------

> ```
> Aşağıdaki örnek, gömülü ikili nesneler olmadan sunumun nasıl yükleneceğini gösterir.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Varsayılan **false** .

**Döndürür:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Aspose.Slides'in sunum yükleme sırasında tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin türleri:

 *  
 *  
 *  

Okuma/yazma  boolean .

--------------------

> ```
> Aşağıdaki örnek, gömülü ikili nesneler olmadan sunumun nasıl yükleneceğini gösterir.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Varsayılan **false** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |