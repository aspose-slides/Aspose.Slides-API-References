---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /id/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

Menyediakan akses mudah ke hyperlink yang terkandung.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkClick tidak null. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Menghapus semua hyperlink HyperlinkClick dan HyperlinkMouseOver yang terkandung (dalam semua subobjek IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```


Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkClick tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Semua subobjek IHyperlinkContainer yang berisi HyperlinkClick tidak null
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```


Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```


Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```


Menghapus semua hyperlink HyperlinkClick dan HyperlinkMouseOver yang terkandung (dalam semua subobjek IHyperlinkContainer).