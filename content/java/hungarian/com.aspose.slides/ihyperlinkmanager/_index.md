---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Hipervonzalak kezelése (hozzáadás és eltávolítás).
type: docs
url: /hu/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Hipervonzalak kezelése (hozzáadás és eltávolítás).

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Külső hiperhivatkozás beállítása kattintáskor. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Belső hiperhivatkozás beállítása kattintáskor. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Hiperhivatkozás eltávolítása kattintáskor. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Külső hiperhivatkozás beállítása egérmutató fölé. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Belső hiperhivatkozás beállítása egérmutató fölé. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Hiperhivatkozás eltávolítása egérmutató fölé. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Makró hiperhivatkozás beállítása kattintáskor. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Külső hiperhivatkozás beállítása kattintáskor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperhivatkozás objektum [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Belső hiperhivatkozás beállítása kattintáskor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperhivatkozás.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Hiperhivatkozás eltávolítása kattintáskor.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Külső hiperhivatkozás beállítása egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperhivatkozás.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Belső hiperhivatkozás beállítása egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperhivatkozás.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Hiperhivatkozás eltávolítása egérmutató fölé.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Makró hiperhivatkozás beállítása kattintáskor.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| macroName | java.lang.String | A makró neve |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hiperhivatkozás objektum [IHyperlink](../../com.aspose.slides/ihyperlink)