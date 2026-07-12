---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Summary Zoom Section nesnelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/summaryzoomsectioncollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Summary Zoom Section nesnelerinin bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Yeni bir Summary Zoom Section nesnesi oluşturur ve koleksiyona ekler |
| [size()](#size--) | Koleksiyonda gerçekten bulunan öğe sayısını alır. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Belirtilen SummaryZoomSection nesnesinin dizinini döndürür. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Summary Zoom Section nesnesini koleksiyondan kaldırır. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Verilen bölüm için Summary Zoom Section öğesini döndürür. |
| [clear()](#clear--) | Koleksiyondan tüm SummaryZoomSection nesnelerini kaldırır. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```


Belirtilen dizindeki öğeyi alır. Salt okunur [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```


Yeni bir Summary Zoom Section nesnesi oluşturur ve koleksiyona ekler

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Yeni bir Summary Zoom Section öğesi için bölüm [ISection](../../com.aspose.slides/isection) |

Eğer bu bölüm için bir öğe zaten koleksiyonda mevcutsa, mevcut öğe döndürülür. |

**Döndürür:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Eklendi [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) öğe
### size() {#size--}
```
public final int size()
```


Koleksiyonda gerçekten bulunan öğe sayısını alır. Salt okunur int.

**Döndürür:**
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```


Belirtilen SummaryZoomSection nesnesinin dizinini döndürür.

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Bulunacak SummaryZoomSection nesnesi [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Döndürür:**
int - SummaryZoomSection nesnesinin dizini veya koleksiyonda olmayan SummaryZoomSection nesnesi ise -1
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```


Summary Zoom Section nesnesini koleksiyondan kaldırır.

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Summary Zoom Section öğesinin kaldırılacağı bölüm [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```


Verilen bölüm için Summary Zoom Section öğesini döndürür.

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Bulunacak bölüm [ISection](../../com.aspose.slides/isection) |

**Döndürür:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) veya bölüm için öğe içermeyen koleksiyonda null
### clear() {#clear--}
```
public final void clear()
```


Koleksiyondan tüm SummaryZoomSection nesnelerini kaldırır.

--------------------

> ```
> Örnek, Summary Zoom Section öğesini indeksle almayı göstermektedir:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki indeks. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```


Koleksiyonu yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - An java.util.Iterator for the entire collection.