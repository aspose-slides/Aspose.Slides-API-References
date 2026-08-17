---
title: SlideCollection
second_title: Aspose.Slides for Java API Referansı
description: Kaydırımların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/slidecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Bir slayt koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Belirtilen slaydın bir kopyasını belirtilen bölümün sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Koleksiyonun sonuna yeni boş bir slayt ekler. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Belirtilen kaynak slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Belirtilen kaynak slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir Java iterator'ı döndürür. |
| [toArray()](#toArray--) | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Slaytları koleksiyondan belirtilen konuma taşır. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Belirtilen slaydın koleksiyondaki indeksini döndürür. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF belgesinden slaytlar oluşturur ve PDF içe aktarma seçeneklerini göz önünde bulundurarak koleksiyonun sonuna ekler. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konuma ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm öğeleri koleksiyondan belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çoklu iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt okunur int.

**Döndürür:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt okunur [Slide](../../com.aspose.slides/slide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |

--------------------

Farklı sunular arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir. Otomatik olarak klonlanan master'ları izlemek ve aynı master slaytının birden fazla kopyasının oluşturulmasını önlemek için dahili bir kayıt defteri kullanılır. Master slaytların manuel klonlanması ne engellenir ne de kayıt altına alınır. Klonlama süreci üzerinde daha fazla kontrol ihtiyacınız varsa \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) veya \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) slaytları klonlamak için, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) veya [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) düzenleri klonlamak için ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master'ları klonlamak için kullanın.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Belirtilen slaydın bir kopyasını belirtilen bölümün sonuna ekler.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Artık ikinci bölümde ilk slaytın bir kopyası bulunuyor.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| section | [ISection](../../com.aspose.slides/isection) | Yeni slayt için bölüm. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını örnekleyin
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // İstenen slaytı aynı sunumdaki slayt koleksiyonunun sonuna klonlayın
>      ISlideCollection slds = pres.getSlides();
>      // İstenen slaytı aynı sunumda belirtilen indekse klonlayın
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Değiştirilmiş sunumu diske kaydedin
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Kaynak sunum dosyasını yüklemek için Presentation sınıfını örnekleyin
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Slaytın klonlanacağı hedef PPTX için Presentation sınıfını örnekleyin
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Hedef sunumu diske kaydedin
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt.

--------------------

Farklı sunular arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir. Otomatik olarak klonlanan master'ları izlemek ve aynı master slaytının birden fazla kopyasının oluşturulmasını önlemek için dahili bir kayıt defteri kullanılır. Master slaytların manuel klonlanması ne engellenir ne de kayıt altına alınır. Daha fazla kontrol ihtiyacınız varsa \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) veya \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) slaytlar için ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master slaytlar için kullanın.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Koleksiyonun sonuna yeni boş bir slayt ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için düzen. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Added slide.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için düzen. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen kaynak slaydın bir kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaydın aynı Tür veya Adı olan düzenidir). Eğer uygun bir düzen yoksa, kaynak slaydın düzeni (allowCloneMissingLayout true ise) klonlanır veya allowCloneMissingLayout false ise PptxEditException yükseltilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master içinde uygun bir düzen yoksa, kaynak slaydın düzeni (allowCloneMissingLayout true ise) klonlanır veya allowCloneMissingLayout false ise PptxEditException yükseltilir. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - New slide.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen kaynak slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaydın aynı Tür veya Adı olan düzenidir). Eğer uygun bir düzen yoksa, kaynak slaydın düzeni (allowCloneMissingLayout true ise) klonlanır veya allowCloneMissingLayout false ise PptxEditException yükseltilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master içinde uygun bir düzen yoksa, kaynak slaydın düzeni (allowCloneMissingLayout true ise) klonlanır veya allowCloneMissingLayout false ise PptxEditException yükseltilir. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Inserted slide.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Kaldırılacak slayt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Tüm koleksiyon için bir Java iterator'ı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Tüm koleksiyon için bir java.util.Iterator.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) dizisi

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenecek ilk slaydın indeksi. |
| count | int | Eklenecek slayt sayısı. |

**Döndürür:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) dizisi
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Slaytı koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Taşınacak slayt. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla indeks'ten itibaren yerleştirilecektir.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Taşınacak slaytlar. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Belirtilen slaytın koleksiyondaki indeksini döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Bulunacak slayt. |

**Döndürür:**
int - Slayt indeksi veya slayt bu koleksiyona ait değilse -1.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| path | java.lang.String | PDF belgesinin yolu |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| path | java.lang.String | PDF belgesinin yolu |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Pdf içe aktarma seçenekleri |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF belgesinin kaynağı olarak kullanılacak akış |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF belgesinin kaynağı olarak kullanılacak akış |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Pdf içe aktarma seçenekleri |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> // Presentation sınıfının bir örneğini oluşturun.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // AddFromHtml metodunu çağırın ve HTML dosyasını geçirin.
>      pres.getSlides().addFromHtml(html);
>      // Dosyayı PowerPoint belgesi olarak kaydetmek için Save metodunu kullanın.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak, eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytta boş bir alandan başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |

**Döndürür:**
com.aspose.slides.ISSlide[] - Eklenen slaytlar

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| useSlideWithIndexAsStart | boolean | Bu bayrak, eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytta boş bir alandan başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |

**Döndürür:**
com.aspose.slides.ISSlide[] - Eklenen slaytlar.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreli bağlantıların çözülmesinde kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak, eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytta boş bir alandan başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISSlide[] - Eklenen slaytlar.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |

**Döndürür:**
com.aspose.slides.ISSlide[] - Eklenen slaytlar

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| useSlideWithIndexAsStart | boolean | Bu bayrak, eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytta boş bir alandan başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISSlide[] - Eklenen slaytlar

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren değeri döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object