---
title: ParagraphCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Paragrafların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/paragraphcollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Paragrafların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okuma olup olmadığını gösteren bir değeri alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Paragrafı koleksiyonun sonuna ekler. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini koleksiyonun sonuna ekler. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Listede belirli bir öğenin dizinini belirler. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Paragrafı koleksiyona belirtilen indekste ekler. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | ParagraphCollection içeriğini koleksiyona belirtilen indekste ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in öğelerini bir Array'e, belirli bir Array indeksinden başlayarak kopyalar. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den belirli bir nesnenin ilk oluşumunu kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getSlide()](#getSlide--) | Paragraflar koleksiyonunun üst slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Paragraflar koleksiyonunun üst sunumunu döndürür. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Belirtilen html dizesinden metni koleksiyona ekler. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür. |

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyonda gerçekte bulunan eleman sayığını alır. Yalnızca okuma int.

**Döndürür:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okuma olup olmadığını gösteren bir değeri alır. Yalnızca okuma boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) yalnızca okuma ise true; aksi takdirde false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Paragrafı koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Koleksiyonun sonuna eklenecek Paragraph. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

ParagraphCollection içeriğini koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Koleksiyonun sonuna eklenecek ParagraphCollection. |

**Döndürür:**
int - Paragraph'ın eklendiği indeks veya eklenecek bir şey yoksa -1.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Listede belirli bir öğenin indeksini belirler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Listede bulunacak nesne. |

**Döndürür:**
int - öğe listede bulunursa indeks; aksi takdirde -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Paragrafı koleksiyona belirtilen indekste ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Paragrafın eklenmesi gereken sıfır tabanlı indeks. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Eklenecek Paragraph. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

ParagraphCollection içeriğini koleksiyona belirtilen indekste ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Paragrafların eklenmesi gereken sıfır tabanlı indeks. |
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
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini bir Array'e, belirli bir Array indeksinden başlayarak kopyalar.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan öğelerin hedefi olan tek boyutlu Array. Array sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı array içindeki sıfır tabanlı indeks. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Koleksiyonun belirtilen indeksteki öğesini kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'den belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kaldırılacak nesne. |

**Döndürür:**
boolean - item [IGenericCollection](../../com.aspose.slides/igenericcollection)'den başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca item orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunmazsa false döndürür.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Koleksiyon içinde yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Koleksiyon içinde yinelemek için kullanılabilecek bir IGenericEnumerator.
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

Paragraflar koleksiyonunun üst slaytını döndürür. Yalnızca okuma [BaseSlide](../../com.aspose.slides/baseslide).

**Döndürür:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Paragraflar koleksiyonunun üst sunumunu döndürür. Yalnızca okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Belirtilen html dizesinden metni koleksiyona ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| text | java.lang.String | HTML metni. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | URI'leri çözen ve referans verilen nesneleri getiren çözümleyici geri çağırma nesnesi. |
| uri | java.lang.String | HTML belgesi eklemek için URI. Göreceli bağlantıları çözmek için kullanılır. |

--------------------
Çözücü (resolver) belirtmek potansiyel olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın.
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Belirtilen paragrafları HTML'e dönüştürür ve String nesnesi olarak döndürür.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| firstParagraphIndex | int | İlk paragraf indeksi int |
| paragraphsCount | int | Paragraf sayısı int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Dönüştürme seçenekleri [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Döndürür:**
java.lang.String - Oluşturulan HTML.