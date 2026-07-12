---
title: IParagraphCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Paragrafların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iparagraphcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Paragraph nesnelerinden oluşan bir koleksiyonu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğe sayısını alır. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Koleksiyonun sonuna bir Paragraph ekler. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini koleksiyonun sonuna ekler. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Belirtilen indekste bir Paragraph ekler. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Belirtilen indekste ParagraphCollection içeriğini ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Belirli bir paragraph'ın ilk görülmesini kaldırır. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Belirtilen html dizesinden metin ekler. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Belirtilen html dizesinden metin ekler. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Belirtilen paragraphları HTML'e dönüştürür ve String nesnesi olarak döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonda gerçekte bulunan öğe sayısını alır. Salt okunur int.

**Dönüş Değeri:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Koleksiyonun sonuna bir Paragraph ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyonun sonuna eklenecek Paragraph. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


ParagraphCollection içeriğini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Koleksiyonun sonuna eklenecek ParagraphCollection. |

**Dönüş Değeri:**
int - Paragraph'ın eklendiği indeks veya ekleyecek bir şey yoksa -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Belirtilen indekste bir Paragraph ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| index | int | Paragraph'ın ekleneceği sıfır tabanlı indeks. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Eklenecek Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


ParagraphCollection içeriğini belirtilen indekste ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- |   |
| index | int | Paragraphların ekleneceği sıfır tabanlı indeks. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Eklenecek paragraphlar. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- |   |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Belirli bir paragraph'ın ilk görülmesini kaldırır.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- |   |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyondan kaldırılacak paragraph. |

**Dönüş Değeri:**
boolean - true if item was successfully removed; otherwise, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Belirtilen html dizesinden metin ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Belirtilen html dizesinden metin ekler.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI'ları çözen ve başvurulan nesneleri getiren çözümleyici geri çağırma nesnesi. |
| uri | java.lang.String | HTML belgesi eklemek için URI. Göreli bağlantıların çözülmesinde kullanılır.

--------------------

Resolver kullanımı bir güvenlik açığı oluşturabilir. Dikkatli kullanın. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Belirtilen paragraphları HTML'e dönüştürür ve String nesnesi olarak döndürür.

**Parametreler:**
| Parametre | Type | Açıklama |
| --- | --- | --- |
| firstParagraphIndex | int | İlk paragraph indeksi |
| paragraphsCount | int | Paragraph sayısı |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Dönüştürme seçenekleri [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Dönüş Değeri:**
java.lang.String - Oluşturulan HTML.