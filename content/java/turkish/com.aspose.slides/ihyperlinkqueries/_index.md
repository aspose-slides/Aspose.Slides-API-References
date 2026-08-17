---
title: IHyperlinkQueries
second_title: Aspose.Slides for Java API Reference
description: İçerdiği köprülere kolay erişim sağlar.
type: docs
url: /tr/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

İçerdiği köprülere kolay erişim sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | null olmayan HyperlinkClick içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Tüm IHyperlinkContainer alt nesnelerinde bulunan HyperlinkClick ve HyperlinkMouseOver köprülerini kaldırır. |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

null olmayan HyperlinkClick içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle köprüsünü yönetebilirsiniz (okuma, güncelleme veya kaldırma). IHyperlinkContainer arabirimine bakın.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkClick
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle köprüsünü yönetebilirsiniz (okuma, güncelleme veya kaldırma). IHyperlinkContainer arabirimine bakın.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle köprüsünü yönetebilirsiniz (okuma, güncelleme veya kaldırma). IHyperlinkContainer arabirimine bakın.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - All IHyperlinkContainer subobjects that contain not null HyperlinkMouseOver
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Tüm IHyperlinkContainer alt nesnelerinde bulunan HyperlinkClick ve HyperlinkMouseOver köprülerini kaldırır.