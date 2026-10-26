---
title: LoadOptions
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumu yüklerken format veya varsayılan yazı tipi gibi ek seçenekler belirtmeye olanak tanır.
type: docs
url: /tr/com.aspose.slides/loadoptions/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Bir sunumu yüklerken ek seçenekler (örneğin format veya varsayılan yazı tipi) belirtmeye olanak tanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Yeni varsayılan yükleme seçenekleri oluşturur. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Yeni yükleme seçenekleri oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Yüklenmek üzere bir sunumun formatını alır veya ayarlar. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Yüklenmek üzere bir sunumun formatını alır veya ayarlar. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır veya ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır veya ayarlar. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Kaynak yazı tipi bulunamadığında kullanılan Simge yazı tipini alır veya ayarlar. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Simge yazı tipini alır veya ayarlar. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır veya ayarlar. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır veya ayarlar. |
| [getPassword()](#getPassword--) | Parolayı alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Parolayı alır veya ayarlar. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | İkili Büyük Nesneler (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder; örneğin geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytları. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | İkili Büyük Nesneler (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder; örneğin geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytları. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Sunum tarafından kullanılacak dış yazı tipleri için kaynakları belirtir. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Sunum tarafından kullanılacak dış yazı tipleri için kaynakları belirtir. |
| [getInterruptionToken()](#getInterruptionToken--) | Kesinti isteklerini izlemek için kullanılan token. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Kesinti isteklerini izlemek için kullanılan token. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Dış kaynakların yüklenmesini yöneten geri çağırma arabirimini alır veya ayarlar. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Dış kaynakların yüklenmesini yöneten geri çağırma arabirimini alır veya ayarlar. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Elektronik tablo seçeneklerini alır. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Elektronik tablo seçeneklerini alır. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Sunum metni için varsayılan dili alır veya ayarlar. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Aspose.Slides'in bir sunumu yüklerken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Aspose.Slides'in bir sunumu yüklerken tüm gömülü ikili nesneleri silip silmeyeceğini belirler. |
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| loadFormat | int | Yüklenmek üzere bir sunumun formatı. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Yüklenmek üzere bir sunumun formatını alır veya ayarlar. Okunur/Yazılır [LoadFormat](../../com.aspose.slides/loadformat).

**Dönüş:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```


Yüklenmek üzere bir sunumun formatını alır veya ayarlar. Okunur/Yazılır [LoadFormat](../../com.aspose.slides/loadformat).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır veya ayarlar. Okunur/Yazılır String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Dönüş:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Kaynak yazı tipi bulunamadığında kullanılan Normal yazı tipini alır veya ayarlar. Okunur/Yazılır String.

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
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


Kaynak yazı tipi bulunamadığında kullanılan Simge yazı tipini alır veya ayarlar. Okunur/Yazılır String.

**Dönüş:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```


Kaynak yazı tipi bulunamadığında kullanılan Simge yazı tipini alır veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```


Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır veya ayarlar. Okunur/Yazılır String.

**Dönüş:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```


Kaynak yazı tipi bulunamadığında kullanılan Asya yazı tipini alır veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Parolayı alır veya ayarlar. Okunur/Yazılır String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // şifrelenmiş sunumla çalış
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Değer: Parola.

**Dönüş:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Parolayı alır veya ayarlar. Okunur/Yazılır String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // şifrelenmiş sunumla çalış
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Değer: Parola.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```


Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. True değeri yalnızca şifreli bir sunum dosyasından belge özelliklerinin yüklenmesi gerektiği ve parolanın yok sayılacağı anlamına gelir. False değeri ise doğru parolanın kullanılmasıyla tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. Okunur/Yazılır boolean.

**Dönüş:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```


Bu özellik, sunum dosyası parola korumalıysa anlamlıdır. True değeri yalnızca şifreli bir sunum dosyasından belge özelliklerinin yüklenmesi gerektiği ve parolanın yok sayılacağı anlamına gelir. False değeri ise doğru parolanın kullanılmasıyla tüm şifreli sunumun yüklenmesi gerektiği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman yok sayılır. Şifreli bir dosyanın belge özellikleri herkese açık değilse ve özellik değeri true ise belge özellikleri yüklenemez ve bir istisna fırlatılır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okunur/Yazılır [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Dönüş:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi alır veya ayarlar. Okunur/Yazılır [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```


İkili Büyük Nesneler (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder; örneğin geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytları. Bu seçenekler, belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketim oranını ayarlamayı amaçlar.

--------------------

Bir Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – yani BLOB bir ses, video veya sunum olabilir.

**Dönüş:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```


İkili Büyük Nesneler (BLOB'lar) işleme davranışını yönetmek için kullanılabilecek seçenekleri temsil eder; örneğin geçici dosyaların kullanımı veya bellek içindeki maksimum BLOB baytları. Bu seçenekler, belirli bir ortam veya gereksinimler için en iyi performans/bellek tüketim oranını ayarlamayı amaçlar.

--------------------

Bir Binary Large Object (BLOB), tek bir varlık olarak depolanan ikili veridir – yani BLOB bir ses, video veya sunum olabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```


Sunum tarafından kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri sunum süresince kullanılabilir ve diğer sunumlarla paylaşılmaz.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
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

**Dönüş:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```


Sunum tarafından kullanılacak dış yazı tipleri için kaynakları belirtir. Bu yazı tipleri sunum süresince kullanılabilir ve diğer sunumlarla paylaşılmaz.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //sunumla çalış
>  //CustomFont1, CustomFont2 ve assets\fonts & global\fonts klasörleri ve alt klasörlerindeki yazı tipleri sunum için kullanılabilir
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```


Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrünü yönetir. Yükleme veya kaydetme gibi uzun süren bir işlem, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metodunun [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılabilir.

**Dönüş:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```


Kesinti isteklerini izlemek için kullanılan token.

--------------------

Bu token, tüm [IPresentation](../../com.aspose.slides/ipresentation) örnek ömrünü yönetir. Yükleme veya kaydetme gibi uzun süren bir işlem, [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) metodunun [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılabilir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```


Dış kaynakların yüklenmesini yöneten geri çağırma arabirimini alır veya ayarlar. Okunur/Yazılır [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Dönüş:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Dış kaynakların yüklenmesini yöneten geri çağırma arabirimini alır veya ayarlar. Okunur/Yazılır [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```


Elektronik tablo seçeneklerini alır. Örneğin, bu seçenekler grafiklerde formüllerin hesaplanmasını etkiler.

**Dönüş:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Elektronik tablo seçeneklerini alır. Örneğin, bu seçenekler grafiklerde formüllerin hesaplanmasını etkiler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```


Sunum metni için varsayılan dili alır veya ayarlar. Okunur/Yazılır String.

--------------------

> ```
> Örnek:
>   
>  // Varsayılan metin kültürünü tanımlamak için yükleme seçeneklerini kullanın
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni dikdörtgen şekil ekle ve metin belirle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölümün dilini kontrol et
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Dönüş:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```


Sunum metni için varsayılan dili alır veya ayarlar. Okunur/Yazılır String.

--------------------

> ```
> Örnek:
>   
>  // Varsayılan metin kültürünü tanımlamak için yükleme seçeneklerini kullanın
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Yeni dikdörtgen şekil ekle ve metin ekle
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // İlk bölümün dilini kontrol et
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```


Aspose.Slides'in bir sunumu yüklerken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin tipleri:

Okunur/Yazılır boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Varsayılan **false**.

**Dönüş:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```


Aspose.Slides'in bir sunumu yüklerken tüm gömülü ikili nesneleri silip silmeyeceğini belirler.

Gömülü ikili nesnelerin tipleri:

Okunur/Yazılır boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Varsayılan **false**.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |