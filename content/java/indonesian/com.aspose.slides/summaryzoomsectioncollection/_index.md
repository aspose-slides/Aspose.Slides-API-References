---
title: SummaryZoomSectionCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi objek Summary Zoom Section.
type: docs
url: /id/com.aspose.slides/summaryzoomsectioncollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Mewakili koleksi objek Summary Zoom Section.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Membuat objek Summary Zoom Section baru dan menambahkannya ke koleksi |
| [size()](#size--) | Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Mengembalikan indeks dari objek SummaryZoomSection yang ditentukan. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Menghapus objek Summary Zoom Section dari koleksi. |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Mengembalikan elemen Summary Zoom Section untuk seksi yang diberikan. |
| [clear()](#clear--) | Menghapus semua objek SummaryZoomSection dari koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan. Hanya-baca [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Membuat objek Summary Zoom Section baru dan menambahkannya ke koleksi

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seksi untuk elemen Summary Zoom Section baru [ISection](../../com.aspose.slides/isection)

Jika elemen untuk seksi ini sudah ada dalam koleksi, elemen yang ada akan dikembalikan. |

**Mengembalikan:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Elemen [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) yang ditambahkan
### size() {#size--}
```
public final int size()
```

Mengambil jumlah elemen yang sebenarnya terkandung dalam koleksi. int hanya-baca.

**Mengembalikan:**
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

Mengembalikan indeks dari objek SummaryZoomSection yang ditentukan.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Objek SummaryZoomSection untuk dicari [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Mengembalikan:**
int - Indeks objek SummaryZoomSection atau -1 jika objek SummaryZoomSection bukan dari koleksi ini.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

Menghapus objek Summary Zoom Section dari koleksi.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seksi yang elemen Summary Zoom Section-nya akan dihapus [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

Mengembalikan elemen Summary Zoom Section untuk seksi yang diberikan.

--------------------

> ```
> Contoh ini menunjukkan cara mengambil elemen Summary Zoom Section berdasarkan indeks:
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seksi untuk dicari [ISection](../../com.aspose.slides/isection) |

**Mengembalikan:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) atau null jika koleksi tidak berisi elemen untuk seksi tersebut.
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua objek SummaryZoomSection dari koleksi.

--------------------

> ```
> Contoh ini menunjukkan cara mengambil elemen Summary Zoom Section berdasarkan indeks:
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

Menyalin seluruh koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target |
| index | int | Indeks dalam array target. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). boolean hanya-baca.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Object hanya-baca.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - java.util.Iterator untuk seluruh koleksi.