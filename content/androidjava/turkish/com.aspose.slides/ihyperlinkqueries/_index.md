---
title: IHyperlinkQueries
second_title: Aspose.Slides for Android via Java API Reference
description: Provide easy access to contained hyperlinks.
type: docs
url: /tr/com.aspose.slides/ihyperlinkqueries/
---```
public interface IHyperlinkQueries
```

İçerilen bağlantılara kolay erişim sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHyperlinkClicks()](#getHyperlinkClicks--) | Null olmayan HyperlinkClick içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [getHyperlinkMouseOvers()](#getHyperlinkMouseOvers--) | Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [getAnyHyperlinks()](#getAnyHyperlinks--) | Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. |
| [removeAllHyperlinks()](#removeAllHyperlinks--) | Tüm IHyperlinkContainer alt nesnelerindeki içerilen HyperlinkClick ve HyperlinkMouseOver bağlantılarını kaldırır. |
### getHyperlinkClicks() {#getHyperlinkClicks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkClicks()
```

Null olmayan HyperlinkClick içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle bağlantısını (okuyabilir, güncelleyebilir veya kaldırabilir) yönetebilirsiniz. IHyperlinkContainer arayüzüne bakın.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Null olmayan HyperlinkClick içeren tüm IHyperlinkContainer alt nesneleri
### getHyperlinkMouseOvers() {#getHyperlinkMouseOvers--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getHyperlinkMouseOvers()
```

Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle bağlantısını (okuyabilir, güncelleyebilir veya kaldırabilir) yönetebilirsiniz. IHyperlinkContainer arayüzüne bakın.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesneleri
### getAnyHyperlinks() {#getAnyHyperlinks--}
```
public abstract System.Collections.Generic.IGenericList<IHyperlinkContainer> getAnyHyperlinks()
```

Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesnelerini al. Verilen IHyperlinkContainer nesnesiyle bağlantısını (okuyabilir, güncelleyebilir veya kaldırabilir) yönetebilirsiniz. IHyperlinkContainer arayüzüne bakın.

**Döndürür:**  
com.aspose.ms.System.Collections.Generic.IGenericList<com.aspose.slides.IHyperlinkContainer> - Null olmayan HyperlinkMouseOver içeren tüm IHyperlinkContainer alt nesneleri
### removeAllHyperlinks() {#removeAllHyperlinks--}
```
public abstract void removeAllHyperlinks()
```

Tüm IHyperlinkContainer alt nesnelerindeki içerilen HyperlinkClick ve HyperlinkMouseOver bağlantılarını kaldırır.