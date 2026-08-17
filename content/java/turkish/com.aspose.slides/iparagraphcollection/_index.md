---
title: IParagraphCollection
second_title: Aspose.Slides for Java API Referansı
description: Paragrafların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iparagraphcollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Paragrafların bir koleksiyonunu temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekten bulunan öğe sayısını alır. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Bir Paragraph'ı koleksiyonun sonuna ekler. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini koleksiyonun sonuna ekler. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Belirtilen indekste bir Paragraph'ı koleksiyona ekler. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini belirtilen indekste koleksiyona ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Belirli bir paragrafın ilk oluşumunu kaldırır. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyonda gerçekten bulunan öğe sayısını alır. Salt okunur int.

**Dönüş:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Bir Paragraph'ı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyonun sonuna eklenecek Paragraph. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

ParagraphCollection içeriğini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Koleksiyonun sonuna eklenecek ParagraphCollection. |

**Dönüş:**
int - Paragraph'ın eklendiği indeks, eklemek için hiçbir şey yoksa -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Belirtilen indekste bir Paragraph'ı koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Paragraph'ın ekleneceği sıfır tabanlı indeks. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Eklenecek Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

ParagraphCollection içeriğini belirtilen indekste koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Paragrafların ekleneceği sıfır tabanlı indeks. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Eklenecek paragraflar. |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Koleksiyondan kaldırılacak belirli bir paragrafın ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyondan kaldırılacak paragraf. |

**Dönüş:**
boolean - öğe başarıyla kaldırıldıysa true; aksi takdirde false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI'leri çözen ve referans verilen nesneleri getiren çözümleyici geri çağırma nesnesi. |
| uri | java.lang.String | HTML belgesini eklemek için URI. Göreceli bağlantıların çözülmesinde kullanılır.

--------------------

Çözümleyiciyi belirtmek potansiyel olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| firstParagraphIndex | int | İlk paragraf indeksi int |
| paragraphsCount | int | Paragraf sayısı int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Dönüştürme seçenekleri [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Dönüş:**
java.lang.String - Oluşturulan HTML.