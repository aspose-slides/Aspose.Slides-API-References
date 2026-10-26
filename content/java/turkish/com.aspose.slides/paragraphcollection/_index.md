---
title: ParagraphCollection
second_title: Aspose.Slides for Java API Referansı
description: Paragrafların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/paragraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Paragraf koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyonda bulunan öğelerin gerçek sayısını döndürür. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'nin yalnızca-okunur olup olmadığını belirten bir değer döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi döndürür. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Bir Paragraph'ı koleksiyonun sonuna ekler. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini koleksiyonun sonuna ekler. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | List içinde belirli bir öğenin indeksini belirler. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Belirtilen dizinde bir Paragraph'ı koleksiyona ekler. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Belirtilen dizinde ParagraphCollection içeriğini koleksiyona ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'nin belirli bir değeri içerip içermediğini belirler. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki öğeyi koleksiyondan kaldırır. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir nesnenin ilk oluşumunu kaldırır. |
| [iterator()](#iterator--) | Koleksiyon üzerinden yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getSlide()](#getSlide--) | Paragraflar koleksiyonunun üst slaydını döndürür. |
| [getPresentation()](#getPresentation--) | Paragraflar koleksiyonunun üst sunumunu döndürür. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür. |
### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyonda bulunan öğelerin gerçek sayısını döndürür. Yalnızca-okunur int.

**Döndürür:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


[IGenericCollection](../../com.aspose.slides/igenericcollection)'nin yalnızca-okunur olup olmadığını belirten bir değer döndürür. Yalnızca-okunur boolean.

**Döndürür:**
boolean - true ise [IGenericCollection](../../com.aspose.slides/igenericcollection) yalnızca okunur; aksi takdirde false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```


Belirtilen dizindeki öğeyi döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```


Bir Paragraph'ı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyonun sonuna eklenecek Paragraph. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```


ParagraphCollection içeriğini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Koleksiyonun sonuna eklenecek ParagraphCollection. |

**Döndürür:**
int - Paragraph'ın eklendiği indeks veya eklenecek bir şey yoksa -1.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```


List içinde belirli bir öğenin indeksini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | List içinde bulunacak nesne. |

**Döndürür:**
int - Öğenin listede bulunduğu indeks; bulunamazsa -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```


Bir Paragraph'ı koleksiyonda belirtilen dizine ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Paragraph'ın ekleneceği sıfır tabanlı indeks. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Eklenecek Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```


ParagraphCollection içeriğini koleksiyonda belirtilen dizine ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Paragrafların ekleneceği sıfır tabanlı indeks. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Eklenecek paragraflar. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde aranacak nesne. |

**Döndürür:**
boolean - true ise [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe bulunmuştur; aksi takdirde false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir diziye kopyalar, belirli bir dizi indeksinden başlayarak.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan öğelerin hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi indeksi. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Koleksiyondaki belirtilen dizindeki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```


[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kaldırılacak nesne. |

**Döndürür:**
boolean - true ise [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde öğe başarıyla kaldırılmıştır; aksi takdirde false. Bu metod ayrıca öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunamazsa false döndürür.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```


Koleksiyon üzerinden yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Tüm koleksiyon için bir java.util.Iterator.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Paragraflar koleksiyonunun üst slaydını döndürür. Yalnızca-okunur [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Paragraflar koleksiyonunun üst sunumunu döndürür. Yalnızca-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```


Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI'leri çözen ve başvurulan nesneleri getiren çözücü geri çağırma nesnesi. |
| uri | java.lang.String | HTML belgesini eklemek için URI. Göreceli bağlantıların çözülmesinde kullanılır.

--------------------

Çözücü belirtmek potansiyel olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```


Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstParagraphIndex | int | İlk paragrafın indeks numarası |
| paragraphsCount | int | Paragraf sayısı |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Dönüştürme seçenekleri [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Döndürür:**
java.lang.String - Oluşturulan HTML.