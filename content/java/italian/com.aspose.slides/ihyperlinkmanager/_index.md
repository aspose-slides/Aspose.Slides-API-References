---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Fornisce la gestione dei collegamenti ipertestuali (aggiunta, rimozione).
type: docs
url: /it/com.aspose.slides/ihyperlinkmanager/
---```java
public interface IHyperlinkManager
```

Fornisce la gestione dei collegamenti ipertestuali (aggiunta, rimozione).

## Metodi

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Imposta un collegamento ipertestuale esterno al clic. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Imposta un collegamento ipertestuale interno al clic. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Rimuove il collegamento ipertestuale al clic. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Imposta un collegamento ipertestuale esterno al passaggio del mouse. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Imposta un collegamento ipertestuale interno al passaggio del mouse. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Rimuove il collegamento ipertestuale al passaggio del mouse. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Imposta un collegamento ipertestuale Macro al clic. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Imposta un collegamento ipertestuale esterno al clic.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del collegamento ipertestuale. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Imposta un collegamento ipertestuale interno al clic.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva di destinazione. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Rimuove il collegamento ipertestuale al clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Imposta un collegamento ipertestuale esterno al passaggio del mouse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del collegamento ipertestuale. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Imposta un collegamento ipertestuale interno al passaggio del mouse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva di destinazione. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Rimuove il collegamento ipertestuale al passaggio del mouse.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Imposta un collegamento ipertestuale Macro al clic.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| macroName | java.lang.String | Nome della macro |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink object [IHyperlink](../../com.aspose.slides/ihyperlink)