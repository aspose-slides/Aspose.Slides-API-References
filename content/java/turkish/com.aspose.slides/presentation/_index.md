---
title: Presentation
second_title: Aspose.Slides for Java API Referansı
description: Microsoft PowerPoint sunumunu temsil eder.
type: docs
url: /tr/com.aspose.slides/presentation/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Microsoft PowerPoint sunumunu temsil eder.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Bir sunum dosyasını temsil eden Presentation nesnesini oluştur
>  Presentation pres = new Presentation();
>  try {
>      // İlk slaytı al
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Tipi çizgi olan bir otomatik şekil ekle
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Sunum dosyasını kaydet.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Presentation içinde desteklenen herhangi bir dosyayı yükle, ör. ppt, pptx, odp vb.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Sunum dosyasını kaydet.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Presentation()](#Presentation--) | Bu yapıcı, yeni bir sunumu sıfırdan oluşturur. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Bu yapıcı, yeni bir sunumu sıfırdan oluşturur. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Bu yapıcı, mevcut bir Sunumu okumanın birincil mekanizmasıdır. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Bu yapıcı, mevcut bir Sunumu okumanın birincil mekanizmasıdır. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Bu yapıcı, Sunumun içeriğinin okunduğu bir kaynak dosya yolunu alır. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Bu yapıcı, Sunumun içeriğinin okunduğu bir kaynak dosya yolunu alır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gerçek HeaderFooter yöneticisini döndürür. |
| [getProtectionManager()](#getProtectionManager--) | Bu sunum için izin yöneticisini alır. |
| [getSlides()](#getSlides--) | Sunumda tanımlı tüm slaytların bir listesini döndürür. |
| [getSections()](#getSections--) | Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. |
| [getSlideSize()](#getSlideSize--) | Slayt boyutu nesnesini döndürür. |
| [getNotesSize()](#getNotesSize--) | Not slaytı boyutu nesnesini döndürür. |
| [getLayoutSlides()](#getLayoutSlides--) | Sunumda tanımlı tüm yerleşim slaytlarının bir listesini döndürür. |
| [getMasters()](#getMasters--) | Sunumda tanımlı tüm ana slaytların bir listesini döndürür. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Not ana yöneticisini döndürür. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Dağıtım ana yöneticisini döndürür. |
| [getFontsManager()](#getFontsManager--) | Yazı tipleri yöneticisini döndürür. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Şekiller için varsayılan metin stilini döndürür. |
| [getCommentAuthors()](#getCommentAuthors--) | Yorum yazarlarının koleksiyonunu döndürür. |
| [getDocumentProperties()](#getDocumentProperties--) | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. |
| [getImages()](#getImages--) | Sunumdaki tüm görüntülerin koleksiyonunu döndürür. |
| [getAudios()](#getAudios--) | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. |
| [getVideos()](#getVideos--) | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Sunumun slayt gösterisi ayarlarını döndürür. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. |
| [getCustomData()](#getCustomData--) | Sunumun özel verilerini döndürür. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Sunumdaki tüm özel veri bölümlerini döndürür. |
| [getVbaProject()](#getVbaProject--) | Sunum makrolarıyla VBA projesini alır veya ayarlar. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Sunum makrolarıyla VBA projesini alır veya ayarlar. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tüm sunum slaytlarında (ana, yerleşim, not slaytları hariç) bulunan tüm köprülinklere kolay erişim sağlar. |
| [getViewProperties()](#getViewProperties--) | Sunum genel görünüm özelliklerini alır. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Sunumdaki ilk slayt numarasını temsil eder. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Sunumdaki ilk slayt numarasını temsil eder. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. |
| [getSlideById(long id)](#getSlideById-long-) | Kimliğe göre bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [getSourceFormat()](#getSourceFormat--) | Sunumun yüklendiği format hakkında bilgi döndürür. |
| [getMasterTheme()](#getMasterTheme--) | Ana temayı döndürür. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Sunumdaki tüm slaytları belirtilen formatta bir dosyaya kaydeder. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sunumdaki tüm slaytları belirtilen formatta bir akışa kaydeder. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Sunumdaki tüm slaytları belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Sunumdaki tüm slaytları belirtilen formatta ve ek seçeneklerle bir akışa kaydeder. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sunumdaki tüm slaytları XAML işaretlemesini temsil eden dosya kümesine kaydeder. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Sunumdaki tüm slaytlar için Image nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Belirtilen sunum slaytları için Küçük Resim Image nesnelerini döndürür. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Tüm sunum slaytları için özel ölçekleme ile Küçük Resim Image nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Belirtilen sunum slaytları için özel ölçekleme ile Küçük Resim Image nesnelerini döndürür. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Belirtilen boyutta tüm sunum slaytları için Küçük Resim Image nesnelerini döndürür. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Belirtilen boyutta, belirtilen sunum slaytları için Küçük Resim Image nesnelerini döndürür. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Belirtilen sunum slaytlarını, sayfa numaraları korunarak, belirtilen formatta bir dosyaya kaydeder. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Belirtilen sunum slaytlarını, sayfa numaraları korunarak, belirtilen formatta bir dosyaya kaydeder. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Belirtilen sunum slaytlarını, sayfa numaraları korunarak, belirtilen formatta bir akışa kaydeder. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Belirtilen sunum slaytlarını, sayfa numaraları korunarak, belirtilen formatta bir akışa kaydeder. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Tüm slaytlardaki tüm geçerli şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [dispose()](#dispose--) | Bu Presentation nesnesi tarafından kullanılan tüm kaynakları serbest bırakır. |
| [getPresentation()](#getPresentation--) | Bir metnin üst sunumunu döndürür. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |
| [refreshChartsData()](#refreshChartsData--) | Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Bu yapıcı, yeni bir sunumu sıfırdan oluşturur. Oluşturulan sunum bir boş slayta sahiptir.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Bu yapıcı, yeni bir sunumu sıfırdan oluşturur. Oluşturulan sunum bir boş slayta sahiptir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Bu yapıcı, mevcut bir Sunumu okumanın birincil mekanizmasıdır.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Bu yapıcı, mevcut bir Sunumu okumanın birincil mekanizmasıdır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Giriş akışı. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Bu yapıcı, Sunumun içeriğinin okunduğu bir kaynak dosya yolunu alır.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Giriş dosyası. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Bu yapıcı, Sunumun içeriğinin okunduğu bir kaynak dosya yolunu alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | java.lang.String | Giriş dosyası. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ek yükleme seçenekleri. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Okuma/Yazma java.util.Date. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanını döndürür veya ayarlar.

**Döndürür:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Okuma/Yazma java.util.Date. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanını döndürür veya ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Gerçek HeaderFooter yöneticisini döndürür. Salt-okunur [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Alt bilgi görünürlüğü için IsFooterVisible özelliği, bir slayt alt bilgi yer tutucusunun bulunmadığını gösterir.
>      {
>          headerFooterManager.setFooterVisibility(true); // SetFooterVisibility metodu, bir slayt alt bilgi yer tutucusunu görünür kılar.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // IsSlideNumberVisible özelliği, bir slayt sayfa numarası yer tutucusunun bulunmadığını gösterir.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // SetSlideNumberVisibility metodu, bir slayt sayfa numarası yer tutucusunu görünür kılar.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // IsDateTimeVisible özelliği, bir slayt tarih-saat yer tutucusunun bulunmadığını gösterir.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // SetFooterVisibility metodu, bir slayt tarih-saat yer tutucusunu görünür kılar.
>      }
>      headerFooterManager.setFooterText("Footer text"); // SetFooterText metodu, slayt alt bilgi yer tutucusuna metin ayarlar.
>      headerFooterManager.setDateTimeText("Date and time text"); // SetDateTimeText metodu, slayt tarih-saat yer tutucusuna metin ayarlar.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // SetFooterAndChildFootersVisibility metodu, ana slaytı ve tüm alt slayt alt bilgi yer tutucularını görünür kılar.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // SetSlideNumberAndChildSlideNumbersVisibility metodu, ana slaytı ve tüm alt slayt sayfa numarası yer tutucularını görünür kılar.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // SetDateTimeAndChildDateTimesVisibility metodu, ana slaytı ve tüm alt slayt tarih-saat yer tutucularını görünür kılar.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // SetFooterAndChildFootersText metodu, ana slaytı ve tüm alt slayt alt bilgi yer tutucularına metin ayarlar.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // SetDateTimeAndChildDateTimesText metodu, ana slaytı ve tüm alt slayt tarih-saat yer tutucularına metin ayarlar.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Bu sunum için izin yöneticisini alır. Salt-okunur [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Döndürür:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Sunumda tanımlı tüm slaytların bir listesini döndürür. Salt-okunur [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation();
>  try
>  {
>      // İlk ISlide'ın arka plan rengini Mavi olarak ayarla
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Arka planı Görüntü ile ayarla
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Görüntüyü ayarla
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Görüntüyü sunumun görüntü koleksiyonuna ekle
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Sunumu diske kaydet
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // 1. slayta daire tipi geçiş uygula
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // 2. slayta tarak tipi geçiş uygula
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Sunumu diske kaydet
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // 1. slayta daire tipi geçiş uygula
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Geçiş süresini 3 saniye olarak ayarla
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // 2. slayta tarak tipi geçiş uygula
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Geçiş süresini 5 saniye olarak ayarla
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // 3. slayta yakınlaştırma tipi geçiş uygula
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Geçiş süresini 7 saniye olarak ayarla
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Sunumu diske kaydet
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. Salt-okunur [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1, newSlide2'de sona erecek ve ardından section2 başlayacak
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Slayt boyutu nesnesini döndürür. Salt-okunur [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Bir sunum dosyasını temsil eden Presentation nesnesini örnekle
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Oluşturulan sunumların slayt boyutunu kaynağınkine ayarla
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // SetSize metodu, içeriği ölçeklendirerek slayt boyutunu sığdırmak için kullanılır
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // SetSize metodu, içeriğin boyutunu maksimize ederek slayt boyutunu ayarlamak için kullanılır
>          // Sunumu diske kaydet
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 kağıt boyutu
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Not slaytı boyutu nesnesini döndürür. Salt-okunur [INotesSize](../../com.aspose.slides/inotessize).

**Döndürür:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Sunumda tanımlı tüm yerleşim slaytlarının bir listesini döndürür. Salt-okunur [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

IMasterSlide.LayoutSlides özelliğini kullanarak yerleşim slaytlarını ekleme/koyma/kaldırma/kopyalama için alternatif API'ye erişebilirsiniz.

**Döndürür:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Sunumda tanımlı tüm ana slaytların bir listesini döndürür. Salt-okunur [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation();
>  try
>  {
>      // Master ISlide'ın arka plan rengini Forest Green (orman yeşili) olarak ayarla
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Sunumu diske kaydet
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekle
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Düzen slaytı tipine göre aramayı dene
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Sunumun bazı düzen tiplerini içermediği durum.
>          // Sunum dosyası yalnızca Boş ve Özel düzen tiplerini içerir.
>          // Ancak Özel tipteki düzen slaytlarının farklı slayt adları vardır,
>          // örneğin "Title", "Title and Content" vb. ve bunları kullanmak mümkündür
>          // adları düzen slaytı seçmek için kullanabilirsiniz.
>          // Ayrıca yer tutucu şekil tiplerini kullanmak da mümkündür. Örneğin,
>          // Başlık slaytı sadece Başlık yer tutucu tipine sahip olmalıdır, vb.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Eklenen düzen slaytı ile boş bir slayt ekle
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Sunumu kaydet
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Not ana yöneticisini döndürür. Salt-okunur [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Döndürür:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Dağıtım ana yöneticisini döndürür. Salt-okunur [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Döndürür:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Yazı tipleri yöneticisini döndürür. Salt-okunur [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Sunumu yükle
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Değiştirilecek kaynak yazı tipini yükle
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Sunumu kaydet
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Şekiller için varsayılan metin stilini döndürür. Salt-okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Yorum yazarlarının koleksiyonunu döndürür. Salt-okunur [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Döndürür:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. Salt-okunur [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Döndürür:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Sunumdaki tüm görüntülerin koleksiyonunu döndürür. Salt-okunur [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // görüntünün ekleneceği yeni bir sunum oluşturur.
>  Presentation pres = new Presentation();
>  try
>  {
>      // sunuma eklemek istediğimiz büyük görüntü dosyamız olduğunu varsayalım
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Görüntüyü sunuma ekleyelim - KeepLocked davranışını seçiyoruz çünkü
>          // "largeImage.png" dosyasına erişmeyi amaçlamıyoruz.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Sunumu kaydeder. Büyük bir sunum çıktısı alınırken bellek tüketimi
>          // pres nesnesinin ömrü boyunca düşük kalır.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Sunuma görüntü ekler
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Daha önce eklenen görüntüye dayanarak slayt 1'de resim çerçevesi oluşturur
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Sunumda yer alan tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okunur [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Sunumda yer alan tüm gömülü video dosyalarının koleksiyonunu döndürür. Salt okunur [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // PPTX'yi temsil eden Presentation sınıfını örnekle
>  Presentation pres = new Presentation();
>  try {
>      // İlk slaytı al
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Videoyu sunuma göm
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Video Çerçevesi ekle
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Videoyu Video Çerçevesine ayarla
>      vf.setEmbeddedVideo(vid);
>      // Videonun Oynatma Modu ve Ses Düzeyini ayarla
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // PPTX dosyasını diske kaydet
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Video eklenecek yeni bir sunum oluşturur
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Videoyu sunuma ekleyelim - KeepLocked davranışını seçiyoruz çünkü
>          //"veryLargeVideo.avi" dosyasına erişmeyi amaçlamıyoruz.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Sunumu kaydeder. Büyük bir sunum çıktısı alınırken bellek tüketimi
>          // pres nesnesinin ömrü boyunca düşük kalır
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Kaynak dosyayı kilitler ve belleğe YÜKLEMEZ
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Presentation örneği oluşturur, "hugePresentationWithAudiosAndVideos.pptx" dosyasını kilitler.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Her videoyu bir dosyaya kaydedelim. Yüksek bellek kullanımını önlemek için bir tampon gerekli
>      // sunumun video akışından yeni oluşturulan video dosyasına veri aktarmak için
>      byte[] buffer = new byte[81024];
>      // Videoları dolaşır
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Sunumun video akışını açar. Lütfen, bilerek özelliklere erişimden kaçındığımızı unutmayın
>          // video.BinaryData gibi - çünkü bu özellik tam video içeren bir bayt dizisi döndürür, bu da
>          // baytların belleğe yüklenmesine yol açar. video.GetStream kullanırız, bu bir Stream döndürür - ve YÜKLEMEZ
>          //  bütün videoyu belleğe yüklememizi gerektirmez.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Bellek tüketimi, video ya da sunum boyutu ne olursa olsun düşük kalacaktır,
>      }
>          // Gerekirse, aynı adımları ses dosyaları için de uygulayabilirsiniz.
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //video çerçevesi ekle
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //küçük resim yükle
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation nesnesini örnekle
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Döndürür:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Sunum için slayt gösterisi ayarlarını döndürür.

**Döndürür:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Sunumu imzalayan imzaların koleksiyonunu döndürür. Salt okunur [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Sunumun özel verilerini döndürür. Salt okunur [ICustomData](../../com.aspose.slides/icustomdata).

**Döndürür:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Sunumdaki tüm özel veri bölümlerini döndürür. Salt okunur ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Tüm özel XML parçalarını yinele
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Sunum makrolarıyla VBA projesini alır veya ayarlar. Okunur/yazılabilir [IVbaProject](../../com.aspose.slides/ivbaproject).

**Döndürür:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Sunum makrolarıyla VBA projesini alır veya ayarlar. Okunur/yazılabilir [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Tüm sunum slaytlarında (ana slayt, düzen, not slaytları hariç) bulunan tüm köprüleri kolayca erişim sağlar. Salt okunur [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Döndürür:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Sunuma ait görünüm özelliklerini alır. Salt okunur [IViewProperties](../../com.aspose.slides/iviewproperties).

**Döndürür:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Sunumdaki ilk slayt numarasını temsil eder

**Döndürür:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Sunumdaki ilk slayt numarasını temsil eder

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Sunum belgesine uygulanan duyarlılık etiketlerinin koleksiyonunu döndürür. Salt okunur [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Politikadan duyarlılık etiketi kimliğini al
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Politikadan Azure AD site tanımlayıcısını al
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
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Id ile bir Slide, MasterSlide veya LayoutSlide döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| id | long | Bir slaytın Id'si. |

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Sunumun yüklendiği formatla ilgili bilgileri döndürür. Salt okunur [SourceFormat](../../com.aspose.slides/sourceformat).

**Döndürür:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Ana temayı döndürür. Salt okunur [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // Sunum dosyasını temsil eden bir presentation nesnesi oluştur
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulan dosyanın yolu. |
| format | int | Dışa aktarılan verinin formatı. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| format | int | Dışa aktarılan verinin formatı. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulan dosyanın yolu. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML formatı seçenekleri. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Sunumun tüm slaytları için Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Belirtilen sunum slaytları için bir Thumbnail Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Sunumun tüm slaytları için özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |
| scaleX | float | Bu Thumbnail'i x ekseninde ölçeklendirecek değer. |
| scaleY | float | Bu Thumbnail'i y ekseninde ölçeklendirecek değer. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Belirtilen sunum slaytları için özelleştirilmiş ölçekleme ile bir Thumbnail Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| scaleX | float | Bu Thumbnail'i x ekseninde ölçeklendirecek değer. |
| scaleY | float | Bu Thumbnail'i y ekseninde ölçeklendirecek değer. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Sunumun tüm slaytları için belirtilen boyutta bir Thumbnail Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Belirtilen sunum slaytları için belirtilen boyutta bir Thumbnail Image nesnelerini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff seçenekleri. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| imageSize | java.awt.Dimension | Oluşturulacak görüntünün boyutu. |

**Döndürür:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulan dosyanın yolu. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Oluşturulan dosyanın yolu. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir akışa kaydeder.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir akışa kaydeder.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; // Dönüşüm işlemini başlat
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following ... ...
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Çıktı akışı. |
| slides | int[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | int | Dışa aktarılan verinin formatı. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ek format seçenekleri. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Tüm slaytlardaki tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir.

### dispose() {#dispose--}
```
public final void dispose()
```

Bu Presentation nesnesi tarafından kullanılan tüm kaynakları serbest bırakır.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Bir metnin ana sunumunu döndürür. Salt okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // tüm ayrı 'the' oluşumlarını vurgulama
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Vurgulanacak metin. |
| highlightColor | java.awt.Color | Metni vurgulamak için renk. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için geri arama nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10 semboldan uzun tüm kelimeleri vurgulama
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| regex | java.util.regex.Pattern | Vurgulanacak dizeleri almak için kullanılan regular expression java.util.regex.Pattern. |
| highlightColor | java.awt.Color | Metni vurgulamak için kullanılan renk. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için kullanılan geri arama nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir.

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
| newText | java.lang.String | oldText'in tüm oluşumlarını değiştirecek dize. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Metin arama seçenekleri [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için kullanılan geri arama nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Regular expression'ın tüm eşleşmelerini belirtilen dizeyle değiştirir.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // 10 sembolden uzun tüm kelimeleri '***' ile değiştir
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Değiştirilecek dizeleri almak için kullanılan regular expression java.util.regex.Pattern. |
| newText | java.lang.String | Değiştirilecek dizelerin tüm oluşumlarını değiştirecek dize. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Arama sonuçlarını almak için kullanılan geri arama nesnesi [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```


Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public final void refreshChartsData(boolean skipFailedCharts)
```


Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skipFailedCharts | boolean | Bir grafiğin güncellenememesi durumunda yenileme işleminin devam edip etmeyeceğini belirler. true ise, istisna oluşturan grafikler atlanır; aksi takdirde istisna yükseltilir. |