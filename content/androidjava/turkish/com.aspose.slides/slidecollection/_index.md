---
title: SlideCollection
second_title: Aspose.Slides for Android Java API Referansı
description: Slaytların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/slidecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleşen Arabirimler:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Bir slayt koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Adds a copy of a specified slide to the end of the collection. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Adds a copy of a specified slide to the end of the specified section. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Adds a new empty slide to the end of the collection. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified slide to specified position of the collection. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Adds a copy of a specified source slide to the end of the collection. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Inserts a copy of a specified source slide to specified position of the collection. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [toArray()](#toArray--) | Creates and returns an array with all slides in it. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all slides from the specified range in it. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Moves slide from the collection to the specified position. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Moves slides from the collection to the specified position. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Returns an index of the specified slide in the collection. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Creates slides from the PDF document and adds them to the end of the collection. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and adds them to the end of the collection. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Creates slides from HTML text and adds them to the end of the collection. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan öğe sayısını alır. Yalnızca okuma int.

**Dönüş Değeri:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Belirtilen indeksdeki öğeyi alır. Yalnızca okuma [Slide](../../com.aspose.slides/slide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt.

--------------------

Farklı sunumlar arasında bir slaytı kopyalarken slaytın master'ı da kopyalanabilir. Otomatik olarak kopyalanan master'ları izlemek için dahili bir kayıt defteri kullanılır; aynı master slaydının birden fazla kopyasının oluşturulması önlenir. Master slaytların manuel kopyalanması ne engellenir ne de kaydedilir. Kopyalama süreci üzerinde daha fazla kontrol ihtiyacınız varsa `#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide)` veya `#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean)` metodlarını kullanın; slayt kopyalamak için [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) veya [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) layout kopyalamak için ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master kopyalamak için.

**Dönüş Değeri:**
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
>      // Artık ikinci bölüm birinci slaydın bir kopyasını içeriyor.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt. |
| section | [ISection](../../com.aspose.slides/isection) | Yeni slayt için bölüm.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Belirtilen slaydın bir kopyasını koleksiyon içinde belirtilen konuma ekler.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Sunum dosyasını temsil eden Presentation sınıfını oluşturur
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // İstenen slaytı aynı sunumdaki slayt koleksiyonunun sonuna kopyalar
>      ISlideCollection slds = pres.getSlides();
>      // İstenen slaytı aynı sunumdaki belirtilen indekse kopyalar
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Değiştirilmiş sunumu diske yazar
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Kaynak sunum dosyasını yüklemek için Presentation sınıfını oluşturur
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Kaydırılacak slaytın hedef PPTX'i için Presentation sınıfını oluşturur
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Hedef sunumu diske yazar
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt.

--------------------

Farklı sunumlar arasında bir slaytı kopyalarken slaytın master'ı da kopyalanabilir. Otomatik olarak kopyalanan master'ları izlemek için dahili bir kayıt defteri kullanılır; aynı master slaydının birden fazla kopyasının oluşturulması önlenir. Master slaytların manuel kopyalanması ne engellenir ne de kaydedilir. Kopyalama süreci üzerinde daha fazla kontrol ihtiyacınız varsa `#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide)` veya `#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean)` metodlarını kullanın; slayt kopyalamak ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master kopyalamak için.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Yeni boş bir slaydı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için layout.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Belirtilen slaydın bir kopyasını koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için layout.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen slaydın bir kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için layout slaytı.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen slaydın bir kopyasını koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için layout slaytı.

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen kaynak slaydın bir kopyasını koleksiyonun sonuna ekler. Uygun layout, belirtilen master'dan otomatik olarak seçilir (uygun layout, kaynak slaydın layout'unun aynı Type veya Name değerine sahip olanıdır). Uygun layout bulunamazsa, kaynak slaydın layout'u kopyalanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master içinde uygun layout bulunmazsa, kaynak slaydın layout'u kopyalanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen kaynak slaydın bir kopyasını koleksiyon içinde belirtilen konuma ekler. Uygun layout, belirtilen master'dan otomatik olarak seçilir (uygun layout, kaynak slaydın layout'unun aynı Type veya Name değerine sahip olanıdır). Uygun layout bulunamazsa, kaynak slaydın layout'u kopyalanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Kopyalanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master içinde uygun layout bulunmazsa, kaynak slaydın layout'u kopyalanır (allowCloneMissingLayout true ise) veya PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

**Dönüş Değeri:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Kaldırılacak slayt.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Koleksiyondan geçmek için bir enumerator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Koleksiyon üzerinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Tüm koleksiyon için bir java.util.Iterator.
### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Koleksiyondaki tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) dizisi
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Eklenmesi gereken ilk slaydın indeksi. |
| count | int | Eklenmesi gereken slayt sayısı. |

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - [Slide](../../com.aspose.slides/slide) dizisi
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Koleksiyondan slaytı belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Taşınacak slayt.

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Koleksiyondaki slaytları belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla, belirtilen indeksten itibaren yerleştirilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Taşınacak slaytlar.

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Koleksiyondaki belirtilen slaydın indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Bulunacak slayt.

**Dönüş Değeri:**
int - Slayt indeksi veya koleksiyonda yer almıyorsa -1.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | PDF belgesinin yolu

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF belgesinden slaytlar oluşturur ve pdf içe aktarma seçeneklerini göz önünde bulundurarak koleksiyonun sonuna ekler.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | java.lang.String | PDF belgesinin yolu |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF içe aktarma seçenekleri

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> Örnek:
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF belgesinin kaynağı olarak kullanılacak akış

**Dönüş Değeri:**
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF belgesinin kaynağı olarak kullanılacak akış |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF içe aktarma seçenekleri

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

--------------------

> ```
> // Presentation sınıfının bir örneğini oluşturur.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // AddFromHtml metodunu çağırır ve HTML dosyasını geçirir.
>          pres.getSlides().addFromHtml(fos);
>          // Save metodunu kullanarak dosyayı PowerPoint belgesi olarak kaydeder.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye yeni bir slayttan mi yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyon içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye yeni bir slayttan mı yoksa belirtilen indeksli slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indeksli slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir.

**Dönüş Değeri:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm öğeleri koleksiyondan belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyon erişiminin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Dönüş Değeri:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Dönüş Değeri:**
java.lang.Object