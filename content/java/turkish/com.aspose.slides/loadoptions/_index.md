---
title: LoadOptions
second_title: Aspose.Slides for Java API Referansı
description: Bir sunumu yüklerken biçim veya varsayılan yazı tipi gibi ek seçenekleri belirtmeye olanak tanır.
type: docs
url: /tr/com.aspose.slides/loadoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Bir sunumu yüklerken ek seçenekleri (örneğin biçim veya varsayılan yazı tipi) belirtmeye olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Yeni varsayılan yükleme seçenekleri oluşturur. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Yeni yükleme seçenekleri oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Bir sunumu yüklemek için biçimi alır ya da ayarlar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Bir sunumu yüklemek için biçimi alır ya da ayarlar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır ya da ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır ya da ayarlar. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini alır ya da ayarlar. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini alır ya da ayarlar. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır ya da ayarlar. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır ya da ayarlar. |
| [getPassword()](#getPassword--) | Şifreyi alır ya da ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Şifreyi alır ya da ayarlar. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır ya da ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır ya da ayarlar. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytı gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytı gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. |
| [getInterruptionToken()](#getInterruptionToken--) | Kesinti isteklerini izlemek için kullanılan token. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Kesinti isteklerini izlemek için kullanılan token. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır ya da ayarlar. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır ya da ayarlar. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Elektronik tablo seçeneklerini alır. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Elektronik tablo seçeneklerini alır. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Sunum metni için varsayılan dili alır ya da ayarlar. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Sunum metni için varsayılan dili alır ya da ayarlar. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides’ın sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides’ın sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Yeni varsayılan yükleme seçenekleri oluşturur.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Yeni yükleme seçenekleri oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loadFormat | int | Yüklenecek bir sunumun biçimi. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Bir sunumu yüklemek için biçimi alır ya da ayarlar. Okuma/Yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Döndürür:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Bir sunumu yüklemek için biçimi alır ya da ayarlar. Okuma/Yazma [LoadFormat](../../com.aspose.slides/loadformat).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Varsayılan normal ve Asya yazı tiplerini tanımlamak için yükleme seçeneklerini kullanın
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Sunumu yükleyin
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Slayt küçük resmini oluştur
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // PDF oluştur
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS oluştur
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini alır ya da ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Sembol yazı tipini alır ya da ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır ya da ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır ya da ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Şifreyi alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // Şifre çözülmüş sunumla çalış
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Değer: Şifre.

**Döndürür:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Şifreyi alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // Şifre çözülmüş sunumla çalış
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Değer: Şifre.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. true değeri, şifre göz ardı edilerek yalnızca belge özelliklerinin şifreli bir sunum dosyasından yüklenmesi gerektiği anlamına gelir. false değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna atılır. Okuma/Yazma boolean.

**Döndürür:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Bu özellik, sunum dosyası şifre korumalıysa anlamlıdır. true değeri, şifre göz ardı edilerek yalnızca belge özelliklerinin şifreli bir sunum dosyasından yüklenmesi gerektiği anlamına gelir. false değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman göz ardı edilir. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna atılır. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır ya da ayarlar. Okuma/Yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Döndürür:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır ya da ayarlar. Okuma/Yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytı gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler, belirli bir ortam veya gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – yani BLOB bir ses, video veya sunum kendisi olabilir.

**Döndürür:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytı gibi Binary Large Objects (BLOB) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder. Bu seçenekler, belirli bir ortam veya gereksinim için en iyi performans/bellek tüketimi oranını ayarlamayı amaçlar.

--------------------

Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – yani BLOB bir ses, video veya sunum kendisi olabilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunum süresince kullanılabilir ve diğer sunumlarla paylaşılmaz.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // sunumla çalış
>  //CustomFont1, CustomFont2 ve assets\fonts & global\fonts klasörlerinden ve alt klasörlerinden gelen yazı tipleri sunumda kullanılabilir
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Sunumda kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri, sunum süresince kullanılabilir ve diğer sunumlarla paylaşılmaz.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrünü yönetir. Yükleme veya kaydetme gibi uzun süren bir işlem, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metodunun [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılır.

**Döndürür:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrünü yönetir. Yükleme veya kaydetme gibi uzun süren bir işlem, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metodunun [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır ya da ayarlar. Okuma/Yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Döndürür:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Dış kaynakların yüklenmesini yöneten geri çağırma arayüzünü alır ya da ayarlar. Okuma/Yazma [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Elektronik tablo seçeneklerini alır. Örneğin, bu seçenekler grafiklerdeki formüllerin hesaplanmasını etkiler.

**Döndürür:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Elektronik tablo seçeneklerini alır. Örneğin, bu seçenekler grafiklerdeki formüllerin hesaplanmasını etkiler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Sunum metni için varsayılan dili alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> Example:
>   
>  // Yükleme seçeneklerini kullanarak varsayılan metin kültürünü tanımlayın
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni dikdörtgen şekil ekle ve metin ekle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölüm dilini kontrol et
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Sunum metni için varsayılan dili alır ya da ayarlar. Okuma/Yazma String.

--------------------

> ```
> Example:
>   
>  // Yükleme seçeneklerini kullanarak varsayılan metin kültürünü tanımlayın
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni dikdörtgen şekil ekle ve metin ekle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölüm dilini kontrol et
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Aspose.Slides’ın sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin türleri:

Okuma/Yazma boolean .

--------------------

> ```
> Aşağıdaki örnek, sunumu gömülü ikili nesneler olmadan nasıl yükleyeceğinizi gösterir.
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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Aspose.Slides’ın sunum yüklenirken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin türleri:

Okuma/Yazma boolean .

--------------------

> ```
> Aşağıdaki örnek, sunumu gömülü ikili nesneler olmadan nasıl yükleyeceğinizi gösterir.
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