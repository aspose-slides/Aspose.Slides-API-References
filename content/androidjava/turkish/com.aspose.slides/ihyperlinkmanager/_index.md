---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Hiperlink yönetimini ekleme ve kaldırma sağlar.
type: docs
url: /tr/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Hiperlink yönetimini (ekleme, kaldırma) sağlar.

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Tıklama sırasında dış hiperlink ayarlar. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Tıklama sırasında iç hiperlink ayarlar. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Tıklama sırasında hiperlink kaldırır. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Üzerine gelindiğinde dış hiperlink ayarlar. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Üzerine gelindiğinde iç hiperlink ayarlar. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Üzerine gelindiğinde hiperlink kaldırır. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Tıklama ile Makro hiperlink ayarlar. |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Tıklama sırasında dış hiperlink ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink nesnesi [IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Tıklama sırasında iç hiperlink ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Tıklama sırasında hiperlink kaldırır.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Üzerine gelindiğinde dış hiperlink ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.lang.String | Hiperlink URL'si. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Üzerine gelindiğinde iç hiperlink ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Hedef slayt. |

**Dönüş:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Üzerine gelindiğinde hiperlink kaldırır.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Tıklama ile Makro hiperlink ayarlar.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperlink nesnesi [IHyperlink](../../com.aspose.slides/ihyperlink)