---
title: IHyperlinkManager
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Biztosítja a hiperhivatkozások kezelését, hozzáadását és eltávolítását.
type: docs
url: /hu/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Biztosítja a hiperhivatkozások kezelését (hozzáadás, eltávolítás).
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```


Beállítja a külső hiperhivatkozást kattintáskor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objektum [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```


Beállítja a belső hiperhivatkozást kattintáskor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```


Eltávolítja a hiperhivatkozást kattintáskor.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```


Beállítja a külső hiperhivatkozást egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| url | java.lang.String | Hiperhivatkozás URL. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```


Beállítja a belső hiperhivatkozást egérmutató fölé.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Cél dia. |

**Visszatérési érték:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```


Eltávolítja a hiperhivatkozást egérmutató fölött.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```


Beállítja a Makró hiperhivatkozást kattintáskor.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink objektum [IHyperlink](../../com.aspose.slides/ihyperlink)