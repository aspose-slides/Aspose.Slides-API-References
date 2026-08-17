---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Köprü yönetimini (ekleme, kaldırma) sağlar.
type: docs
url: /tr/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Köprü yönetimini (ekleme, kaldırma) sağlar.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Tıklama ile harici köprü ayarlar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Tıklama ile dahili köprü ayarlar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tıklama ile köprüyü kaldırır. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Fare üzerine gelindiğinde harici köprü ayarlar. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Fare üzerine gelindiğinde dahili köprü ayarlar. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Fare üzerine gelindiğinde köprüyü kaldırır. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Tıklama ile Makro köprüsü ayarlar. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Tıklama ile harici köprü ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Köprü URL’si. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink nesnesi [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Tıklama ile dahili köprü ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Tıklama ile köprüyü kaldırır.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Fare üzerine gelindiğinde harici köprü ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Köprü URL’si. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Fare üzerine gelindiğinde dahili köprü ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Fare üzerine gelindiğinde köprüyü kaldırır.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Tıklama ile Makro köprüsü ayarlar.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| macroName | java.lang.String | Makronun adı |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink nesnesi [IHyperlink](../../com.aspose.slides/ihyperlink)