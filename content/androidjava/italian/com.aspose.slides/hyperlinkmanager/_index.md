---
title: HyperlinkManager
second_title: Riferimento API Java di Aspose.Slides per Android
description: Fornisce la gestione dei collegamenti ipertestuali (aggiunta e rimozione).
type: docs
url: /it/com.aspose.slides/hyperlinkmanager/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Fornisce la gestione dei collegamenti ipertestuali (aggiunta, rimozione).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Imposta un collegamento ipertestuale esterno al clic. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Imposta un collegamento ipertestuale interno al clic. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Rimuove il collegamento ipertestuale al clic. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Imposta un collegamento ipertestuale esterno al passaggio del mouse. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Imposta un collegamento ipertestuale interno al passaggio del mouse. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Rimuove il collegamento ipertestuale al passaggio del mouse. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Imposta un collegamento ipertestuale Macro al clic. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Imposta un collegamento ipertestuale esterno al clic.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Istanzia una classe Presentation che rappresenta un PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Ottiene la prima diapositiva nella presentazione
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Aggiunge un oggetto AutoShape con tipo impostato a Rectangle
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Converte la forma in AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accede alla proprietà ITextFrame associata all'AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Aggiunge del testo al frame
>      portion.setText("Aspose.Slides");
>      // Imposta il collegamento ipertestuale per il testo della porzione
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Salva la presentazione PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | java.lang.String | URL del collegamento ipertestuale. |

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
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
public final void removeHyperlinkClick()
```

Rimuove il collegamento ipertestuale al clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
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
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
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
public final void removeHyperlinkMouseOver()
```

Rimuove il collegamento ipertestuale al passaggio del mouse.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
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
[IHyperlink](../../com.aspose.slides/ihyperlink) - oggetto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.