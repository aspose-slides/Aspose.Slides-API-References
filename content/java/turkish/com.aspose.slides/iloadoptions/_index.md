---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Sunum yüklenirken (format veya varsayılan yazı tipi gibi) ek seçenekleri belirtmeye olanak tanır.
type: docs
url: /tr/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Sunum yüklenirken (format veya varsayılan yazı tipi gibi) ek seçenekleri belirtmeye olanak tanır.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Yüklenmekte olan bir sunumun formatını alır veya ayarlar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Yüklenmekte olan bir sunumun formatını alır veya ayarlar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılacak Normal yazı tipini alır veya ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılacak Normal yazı tipini alır veya ayarlar. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Kaynak yazı tipi bulunamadığında kullanılacak Simge yazı tipini alır veya ayarlar. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılacak Simge yazı tipini alır veya ayarlar. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Kaynak yazı tipi bulunamadığında kullanılacak Asya yazı tipini alır veya ayarlar. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılacak Asya yazı tipini alır veya ayarlar. |
| [getPassword()](#getPassword--) | Parolayı alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Parolayı alır veya ayarlar. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Bu özellik, sunum dosyası parola ile korunuyorsa anlam kazanır. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Bu özellik, sunum dosyası parola ile korunuyorsa anlam kazanır. |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Geçici dosyaların kullanımı veya bellek içinde maksimum BLOB baytları gibi Binary Large Objects (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Geçici dosyaların kullanımı veya bellek içinde maksimum BLOB baytları gibi Binary Large Objects (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Sunum tarafından kullanılacak harici yazı tiplerinin kaynaklarını belirtir. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Sunum tarafından kullanılacak harici yazı tiplerinin kaynaklarını belirtir. |
| [getInterruptionToken()](#getInterruptionToken--) | Kesinti isteklerini izlemek için kullanılan belirteç. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Kesinti isteklerini izlemek için kullanılan belirteç. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Harici kaynakların yüklenmesini yöneten geri arama arabirimini alır veya ayarlar. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Harici kaynakların yüklenmesini yöneten geri arama arabirimini alır veya ayarlar. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Ek elektronik tablo davranışını belirtmek için kullanılabilecek seçenekleri temsil eder. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Ek elektronik tablo davranışını belirtmek için kullanılabilecek seçenekleri temsil eder. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Yüklenmekte olan bir sunumun formatını alır veya ayarlar. Okuma/yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Yüklenmekte olan bir sunumun formatını alır veya ayarlar. Okuma/yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Kaynak yazı tipi bulunamadığında kullanılacak Normal yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılacak Normal yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Kaynak yazı tipi bulunamadığında kullanılacak Simge yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılacak Simge yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Kaynak yazı tipi bulunamadığında kullanılacak Asya yazı tipini alır veya ayarlar. Okuma-yazma String.

**Döndürür:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılacak Asya yazı tipini alır veya ayarlar. Okuma-yazma String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Parolayı alır veya ayarlar. Okuma-yazma String.

Value: The password.

**Döndürür:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Parolayı alır veya ayarlar. Okuma-yazma String.

Value: The password.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Bu özellik, sunum dosyası parola ile korunuyorsa anlam kazanır. true değeri, şifrelenmiş bir sunum dosyasından yalnızca belge özelliklerinin yüklenmesi gerektiğini ve parolanın göz ardı edileceğini gösterir. false değeri, doğru parola kullanılarak tüm şifreli sunumun yüklenmesi gerektiğini gösterir. Sunum şifrelenmemişse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve istisna fırlatılır. Okuma-yazma boolean.

**Döndürür:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Bu özellik, sunum dosyası parola ile korunuyorsa anlam kazanır. true değeri, şifrelenmiş bir sunum dosyasından yalnızca belge özelliklerinin yüklenmesi gerektiğini ve parolanın göz ardı edileceğini gösterir. false değeri, doğru parola kullanılarak tüm şifreli sunumun yüklenmesi gerektiğini gösterir. Sunum şifrelenmemişse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri halka açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve istisna fırlatılır. Okuma-yazma boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okuma/yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Döndürür:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okuma/yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Geçici dosyaların kullanımı veya bellek içinde maksimum BLOB baytları gibi Binary Large Objects (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler belirli bir ortam veya gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Döndürür:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Geçici dosyaların kullanımı veya bellek içinde maksimum BLOB baytları gibi Binary Large Objects (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler belirli bir ortam veya gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Sunum tarafından kullanılacak harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun yaşam süresi boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz.

**Döndürür:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Sunum tarafından kullanılacak harici yazı tiplerinin kaynaklarını belirtir. Bu yazı tipleri, sunumun yaşam süresi boyunca kullanılabilir ve diğer sunumlarla paylaşılmaz.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Kesinti isteklerini izlemek için kullanılan belirteç.

--------------------

Bu belirteç tüm [IPresentation](../../com.aspose.slides/ipresentation) örneğinin ömrünü yönetir. Sunum yükleme veya kaydetme gibi uzun süren işlemler, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metodunun [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) üzerinden çağrılmasıyla kesilir.

**Döndürür:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Kesinti isteklerini izlemek için kullanılan belirteç.

--------------------

Bu belirteç tüm [IPresentation](../../com.aspose.slides/ipresentation) örneğinin ömrünü yönetir. Sunum yükleme veya kaydetme gibi uzun süren işlemler, [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) metodunun [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) üzerinden çağrılmasıyla kesilir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Harici kaynakların yüklenmesini yöneten geri arama arabirimini alır veya ayarlar. Okuma/yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Döndürür:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Harici kaynakların yüklenmesini yöneten geri arama arabirimini alır veya ayarlar. Okuma/yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Ek elektronik tablo davranışını belirtmek için kullanılabilecek seçenekleri temsil eder.

**Döndürür:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Ek elektronik tablo davranışını belirtmek için kullanılabilecek seçenekleri temsil eder.

**Parametreler:**
| Parameter | Type | Description |
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
>   // Yükleme seçeneklerini kullanarak varsayılan metin kültürünü tanımlayın
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setDefaultTextLanguage("en-US");
>   Presentation pres = new Presentation(loadOptions);
>   try {
>       // Metin içeren yeni bir dikdörtgen şekil ekleyin
>       IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>       shp.getTextFrame().setText("New Text");
>       // İlk bölümün dilini kontrol edin
>       System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>   } finally {
>       if (pres != null) pres.dispose();
>   }
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
>   // Yükleme seçeneklerini kullanarak varsayılan metin kültürünü tanımlayın
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setDefaultTextLanguage("en-US");
>   Presentation pres = new Presentation(loadOptions);
>   try {
>       // Metin içeren yeni bir dikdörtgen şekil ekleyin
>       IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>       shp.getTextFrame().setText("New Text");
>       // İlk bölümün dilini kontrol edin
>       System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

The types of the embedded binary objects:

 *  
 *  
 *  

Okuma/yazma  boolean .

--------------------

> ```
> Aşağıdaki örnek, sunumu herhangi bir gömülü ikili nesne olmadan nasıl yükleyeceğinizi gösterir.
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

Aspose.Slides'in sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

The types of the embedded binary objects:

 *  
 *  
 *  

Okuma/yazma  boolean .

--------------------

> ```
> Aşağıdaki örnek, sunumu herhangi bir gömülü ikili nesne olmadan nasıl yükleyeceğinizi gösterir.
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |