---
title: IPresentation
second_title: Java API Referansı ile Android için Aspose.Slides
description: Sunum belgesi
type: docs
url: /tr/com.aspose.slides/ipresentation/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Sunum belgesi
## Yöntemler

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Sunumun HeaderFooter yöneticisini döndürür. |
| [getProtectionManager()](#getProtectionManager--) | Bu sunum için izin yöneticisini alır. |
| [getSlides()](#getSlides--) | Sunumda tanımlı tüm slaytların bir listesini döndürür. |
| [getSections()](#getSections--) | Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. |
| [getSlideSize()](#getSlideSize--) | Slayt boyutu nesnesini döndürür. |
| [getNotesSize()](#getNotesSize--) | Not slaytı boyutu nesnesini döndürür. |
| [getLayoutSlides()](#getLayoutSlides--) | Sunumda tanımlı tüm yerleşim slaytlarının bir listesini döndürür. |
| [getMasters()](#getMasters--) | Sunumda tanımlı tüm ana slaytların bir listesini döndürür. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Not ana yöneticisini döndürür. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | El dağıtım ana yöneticisini döndürür. |
| [getFontsManager()](#getFontsManager--) | Yazı tipleri yöneticisini döndürür. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Şekiller için varsayılan metin stilini döndürür. |
| [getCommentAuthors()](#getCommentAuthors--) | Yorum yazarlarının koleksiyonunu döndürür. |
| [getDocumentProperties()](#getDocumentProperties--) | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. |
| [getImages()](#getImages--) | Sunumdaki tüm görüntülerin koleksiyonunu döndürür. |
| [getAudios()](#getAudios--) | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. |
| [getVideos()](#getVideos--) | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. |
| [getCustomData()](#getCustomData--) | Sunumun özel verilerini döndürür. |
| [getVbaProject()](#getVbaProject--) | Sunum makrolarıyla VBA projesini alır. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Sunum makrolarıyla VBA projesini alır. |
| [getSourceFormat()](#getSourceFormat--) | Sunumun yüklendiği format hakkında bilgi döndürür. |
| [getMasterTheme()](#getMasterTheme--) | Sunumun ana teması döndürür. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tüm sunum slaytlarında (ana, yerleşim, not slaytları hariç) bulunan tüm köprü bağlantılarına kolay erişim sağlar. |
| [getViewProperties()](#getViewProperties--) | Sunum genişliğindeki görünüm özelliklerini alır. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Sunumdaki ilk slayt numarasını temsil eder. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Sunumdaki ilk slayt numarasını temsil eder. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Sunumdaki tüm özel veri bölümlerini döndürür. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Belirtilen formatta bir dosyaya sunumun tüm slaytlarını kaydeder. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Belirtilen formatta bir akışa sunumun tüm slaytlarını kaydeder. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Belirtilen formatta bir dosyaya ve ek seçeneklerle sunumun tüm slaytlarını kaydeder. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Belirtilen formatta bir akışa ve ek seçeneklerle sunumun tüm slaytlarını kaydeder. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Belirtilen formatta bir dosyaya sunumun seçilen slaytlarını kaydeder. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Belirtilen formatta bir dosyaya sunumun seçilen slaytlarını kaydeder. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Belirtilen formatta bir akışa sunumun seçilen slaytlarını kaydeder. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Belirtilen formatta bir akışa sunumun seçilen slaytlarını kaydeder. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dizi dosyaya kaydeder. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Sunumun tüm slaytları için Küçük Resim nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Belirtilen slaytlar için Küçük Resim IImage nesnelerini döndürür. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Sunumun tüm slaytları için özel ölçeklendirme ile Küçük Resim nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Belirtilen slaytlar için özel ölçeklendirme ile Küçük Resim nesnelerini döndürür. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Sunumun tüm slaytları için belirtilen boyutta Küçük Resim nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Belirtilen slaytlar için belirtilen boyutta Küçük Resim nesnelerini döndürür. |
| [getSlideById(long id)](#getSlideById-long-) | Id ile bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm slaytlardaki tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Belirtilen metnin tüm görülüşlerini başka bir metinle değiştirir. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. Bu Presentation nesnesinin oluşturulma zamanı varsayılan olarak. Okuma/yazma java.util.Date.

**Döndürür:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. Bu Presentation nesnesinin oluşturulma zamanı varsayılan olarak. Okuma/yazma java.util.Date.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Sunumun HeaderFooter yöneticisini döndürür. Salt okuma [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Döndürür:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Bu sunum için izin yöneticisini alır. Salt okuma [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Döndürür:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Sunumda tanımlı tüm slaytların bir listesini döndürür. Salt okuma [ISlideCollection](../../com.aspose.slides/islidecollection).

**Döndürür:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. Salt okuma [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Döndürür:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Slayt boyutu nesnesini döndürür. Salt okuma [ISlideSize](../../com.aspose.slides/islidesize).

**Döndürür:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Not slaytı boyutu nesnesini döndürür. Salt okuma [INotesSize](../../com.aspose.slides/inotessize).

**Döndürür:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Sunumda tanımlı tüm yerleşim slaytlarının bir listesini döndürür. Salt okuma [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Bu slaytların eklenmesi/kaldırılması/klonlanması için alternatif API’ye IMasterSlide.LayoutSlides özelliği üzerinden erişebilirsiniz.

**Döndürür:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Sunumda tanımlı tüm ana slaytların bir listesini döndürür. Salt okuma [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Döndürür:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Not ana yöneticisini döndürür. Salt okuma [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Döndürür:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

El dağıtım ana yöneticisini döndürür. Salt okuma [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Döndürür:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Yazı tipleri yöneticisini döndürür. Salt okuma [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Döndürür:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Şekiller için varsayılan metin stilini döndürür. Salt okuma [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Yorum yazarlarının koleksiyonunu döndürür. Salt okuma [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Döndürür:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. Salt okuma [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Döndürür:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Sunumdaki tüm görüntülerin koleksiyonunu döndürür. Salt okuma [IImageCollection](../../com.aspose.slides/iimagecollection).

**Döndürür:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okuma [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Döndürür:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. Salt okuma [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Döndürür:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Sunumun özel verilerini döndürür. Salt okuma [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Sunum makrolarıyla VBA projesini alır. Okuma/yazma [IVbaProject](../../com.aspose.slides/ivbaproject).

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Sunum makrolarıyla VBA projesini alır. Okuma/yazma [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Sunumun yüklendiği format hakkında bilgi döndürür. Salt okuma [SourceFormat](../../com.aspose.slides/sourceformat).

**Döndürür:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Sunumun ana teması döndürür. Salt okuma [IMasterTheme](../../com.aspose.slides/imastertheme).

**Döndürür:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Tüm sunum slaytlarında (ana, yerleşim, not slaytları hariç) bulunan tüm köprü bağlantılarına kolay erişim sağlar. Salt okuma [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Sunum genişliğindeki görünüm özelliklerini alır. Salt okuma [IViewProperties](../../com.aspose.slides/iviewproperties).

**Döndürür:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Sunumdaki ilk slayt numarasını temsil eder. Okuma/yazma int.

**Döndürür:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Sunumdaki ilk slayt numarasını temsil eder. Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Sunumdaki tüm özel veri bölümlerini döndürür. Salt okuma ICustomXmlPart[].

**Döndürür:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. Salt okuma [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Salt okuma [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Uygulanan etiketleri yazdır
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Yeni etiketi ekle
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Duyarlılık etiketinin kimliğini politikadan al
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Azure AD site tanımlayıcısını politikadan al
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Belirtilen formatta bir dosyaya sunumun tüm slaytlarını kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulacak dosyanın yolu. |
| format | int | Dışa aktarılan verinin formatı. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Belirtilen formatta bir akışa sunumun tüm slaytlarını kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| format | int | Dışa aktarılan verinin formatı. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Belirtilen formatta bir dosyaya ve ek seçeneklerle sunumun tüm slaytlarını kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulacak dosyanın yolu. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Belirtilen formatta bir akışa ve ek seçeneklerle sunumun tüm slaytlarını kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulacak dosyanın yolu. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulacak dosyanın yolu. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Belirtilen slaytları belirtilen formatta bir akışa kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Belirtilen slaytları belirtilen formatta bir akışa kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dizi dosyaya kaydeder.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML format seçenekleri. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Sunumun tüm slaytları için Küçük Resim nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |

**Döndürür:**
com.aspose.slides.IImage[] - IImage nesneleri.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Belirtilen slaytlar için Küçük Resim IImage nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |

**Döndürür:**
com.aspose.slides.IImage[] - IImage nesneleri.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Tüm slaytlar için özel ölçeklendirme ile Küçük Resim nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| scaleX | float | Bu Küçük Resmin x eksenindeki ölçek değeri. |
| scaleY | float | Bu Küçük Resmin y eksenindeki ölçek değeri. |

**Döndürür:**
com.aspose.slides.IImage[] - Bitmap nesneleri.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Belirtilen slaytlar için özel ölçeklendirme ile Küçük Resim nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| scaleX | float | Bu Küçük Resmin x eksenindeki ölçek değeri. |
| scaleY | float | Bu Küçük Resmin y eksenindeki ölçek değeri. |

**Döndürür:**
com.aspose.slides.IImage[] - IImage nesneleri.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Belirtilen boyutta tüm slaytlar için Küçük Resim nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
com.aspose.slides.IImage[] - IImage nesneleri.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Belirtilen slaytlar için belirtilen boyutta Küçük Resim nesnelerini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |
| slides | int[] | 1’den başlayan slayt konumlarını içeren dizi. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
com.aspose.slides.IImage[] - IImage nesneleri.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Id ile bir Slide, MasterSlide veya LayoutSlide döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | long | Bir slaytın Id’si. |

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide nesnesi.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Tüm slaytlardaki tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip bölümleri birleştirir.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // tüm ayrı 'the' oluşumlarını vurgulama
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // tüm ayrı 'the' oluşumlarını vurgulama
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // tüm ayrı 'the' oluşumlarını vurgulama
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Vurgulanacak dizeleri elde etmek için java.util.regex.Pattern düzenli ifadesi. |
| highlightColor | java.lang.Integer | Metni vurgulamak için renk. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Belirtilen metnin tüm görülüşlerini başka bir metinle değiştirir.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Tüm ayrı 'the' oluşumlarını '***' ile değiştir
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| oldText | java.lang.String | Değiştirilecek dize. |
| newText | java.lang.String | oldText’in tüm görülüşlerini değiştirecek dize. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // tüm ayrı 'the' oluşumlarını '***' ile değiştir
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Değiştirilecek dizeleri elde etmek için java.util.regex.Pattern düzenli ifadesi. |
| newText | java.lang.String | Değiştirilecek dizelerin tüm görülüşlerini değiştirecek dize. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri çağırma nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |