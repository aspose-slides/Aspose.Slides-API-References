---
title: IHyperlinkQueries
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menyediakan akses mudah ke hyperlink yang terkandung.
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
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Menghapus semua hyperlink HyperlinkClick dan HyperlinkMouseOver yang terkandung (di semua subobjek IHyperlinkContainer). |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkClick tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Dapatkan semua subobjek IHyperlinkContainer yang berisi HyperlinkMouseOver tidak null. Dengan objek IHyperlinkContainer yang diberikan, Anda dapat mengelola hyperlink-nya (membaca, memperbarui, atau menghapus). Lihat antarmuka IHyperlinkContainer.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Menghapus semua hyperlink HyperlinkClick dan HyperlinkMouseOver yang terkandung (di semua subobjek IHyperlinkContainer).