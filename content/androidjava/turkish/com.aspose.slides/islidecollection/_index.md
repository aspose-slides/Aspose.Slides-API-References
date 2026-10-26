---
title: ISlideCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slayt koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/islidecollection/
---
**Tüm Gerçekleştirilen Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Bir slayt koleksiyonunu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Belirtilen bir slaydın kopyasını belirtilen bölümün sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Koleksiyonun sonuna yeni boş bir slayt ekler. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Belirtilen kaynak slaydın bir kopyasını koleksiyonun sonuna ekler. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Belirtilen kaynak slaydın bir kopyasını koleksiyonun belirtilen konumuna ekler. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [toArray()](#toArray--) | Tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Slaytı koleksiyondan belirtilen konuma taşır. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla, indeksden başlayarak yerleştirilecektir. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Belirtilen slaydın koleksiyondaki indeksini döndürür. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | PDF belgesinden slaytlar oluşturur ve PDF içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt okunur [ISlide](../../com.aspose.slides/islide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |

--------------------

Farklı sunumlar arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir. İç kayıt defteri, aynı master slaydının birden fazla kopyasını önlemek için otomatik olarak klonlanan master'ları izlemek üzere kullanılır. Master slaytların manuel klonlanması ne önlenmez ne de kaydedilir. Klonlama sürecinde daha fazla kontrol gerekirse \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) veya \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) slaytları klonlamak için, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) veya [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) düzenleri klonlamak için ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master'ları klonlamak için kullanılabilir.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Belirtilen bir slaydın kopyasını belirtilen bölümün sonuna ekler.

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
>      // Şimdi ikinci bölüm, ilk slaydın bir kopyasını içeriyor.
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
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |

--------------------

Farklı sunumlar arasında bir slaytı klonlarken slaytın master'ı da klonlanabilir. İç kayıt defteri, aynı master slaydının birden fazla kopyasını önlemek için otomatik olarak klonlanan master'ları izlemek üzere kullanılır. Manual klonlama ne önlenmez ne de kaydedilir. Daha fazla kontrol için \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) veya \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) slaytları klonlamak ve [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) master'ları klonlamak için kullanılabilir.

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Koleksiyonun sonuna yeni boş bir slayt ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için düzen. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slayt için düzen. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen bir slaydın kopyasını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Yeni slayt için düzen slaytı. |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen bir kaynak slaydın kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaydın düzeniyle aynı Type veya Name değerine sahip düzendir). Uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da allowCloneMissingLayout false ise PptxEditException fırlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master'da uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Yeni slayt.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Belirtilen bir kaynak slaydın kopyasını koleksiyonun belirtilen konumuna ekler. Uygun düzen, belirtilen master'dan otomatik olarak seçilir (uygun düzen, kaynak slaydın düzeniyle aynı Type veya Name değerine sahip düzendir). Uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da allowCloneMissingLayout false ise PptxEditException fırlatılır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni slaydın indeksi. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Klonlanacak slayt. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Yeni slayt için master slayt. |
| allowCloneMissingLayout | boolean | Belirtilen master'da uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

**Döndürür:**
[ISlide](../../com.aspose.slides/islide) - Eklenen slayt.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Koleksiyondan kaldırılacak slayt. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) dizisi
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm slaytları içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | İlk eklenen slaydın indeksi. |
| count | int | Eklenecek slayt sayısı. |

**Döndürür:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) dizisi
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Slaytı koleksiyondan belirtilen konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slide | [ISlide](../../com.aspose.slides/islide) | Taşınacak slayt. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Slaytları koleksiyondan belirtilen konuma taşır. Slaytlar, listedeki göründükleri sırayla, indeksden başlayarak yerleştirilecektir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Hedef indeks. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Taşınacak slaytlar. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Belirtilen slaydın koleksiyondaki indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Bulunacak slayt. |

**Döndürür:**
int - Slaydın indeksi veya -1, slayt bu koleksiyondan değilse.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
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
| path | java.lang.String | PDF belgesinin yolu |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

PDF belgesinden slaytlar oluşturur ve PDF içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler.

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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF içe aktarma seçenekleri |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | PDF içe aktarma seçenekleri |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | java.io.InputStream | PDF belgesinin kaynağı olarak kullanılacak akış |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | java.lang.String | Eklenecek HTML. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indekste bulunan slayttan mı. **true** ise veri ekleme belirtilen indekste bulunan slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlText | java.lang.String | Eklenecek HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indekste bulunan slayttan mı. **true** ise veri ekleme belirtilen indekste bulunan slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indekste bulunan slayttan mı. **true** ise veri ekleme belirtilen indekste bulunan slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

HTML metninden slaytlar oluşturur ve koleksiyona belirtilen konumda ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Eklenecek konum. |
| htmlStream | java.io.InputStream | HTML dosyasının kaynağı olarak kullanılacak akış. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Dış nesneleri almak için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | java.lang.String | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | boolean | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen indekste bulunan slayttan mı. **true** ise veri ekleme belirtilen indekste bulunan slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

**Döndürür:**
com.aspose.slides.ISlide[] - Eklenen slaytlar.