---
title: IHyperlinkManager
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Fornisce la gestione dei collegamenti ipertestuali, aggiunta e rimozione.
type: docs
url: /it/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Fornisce la gestione dei collegamenti ipertestuali (aggiunta, rimozione).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Imposta collegamento ipertestuale esterno al click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Imposta collegamento ipertestuale interno al click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Rimuove collegamento ipertestuale al click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Imposta collegamento ipertestuale esterno al passaggio del mouse. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Imposta collegamento ipertestuale interno al passaggio del mouse. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Rimuove collegamento ipertestuale al passaggio del mouse. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Imposta collegamento ipertestuale Macro al click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Imposta collegamento ipertestuale esterno al click.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del Hyperlink. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - oggetto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Imposta collegamento ipertestuale interno al click.

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

Rimuove collegamento ipertestuale al click.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Imposta collegamento ipertestuale esterno al passaggio del mouse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del Hyperlink. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Imposta collegamento ipertestuale interno al passaggio del mouse.

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

Rimuove collegamento ipertestuale al passaggio del mouse.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Imposta collegamento ipertestuale Macro al click.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - oggetto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)