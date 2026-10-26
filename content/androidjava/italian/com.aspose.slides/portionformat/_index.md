---
title: PortionFormat
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Questa classe contiene le proprietà di formattazione della porzione di testo.
type: docs
url: /it/com.aspose.slides/portionformat/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Questa classe contiene le proprietà di formattazione della porzione di testo. Diversamente da [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Istanzia un oggetto presentazione che rappresenta un file di presentazione
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides utilizza questi identificatori speciali (simili a quelli usati in PowerPoint):
>      // +mn-lt - Font latino del corpo (Font latino minore)
>      // +mj-lt -Font latino dell'intestazione (Font latino principale)
>      // +mn-ea - Font dell'Est asiatico del corpo (Font est-asiatico minore)
>      // +mj-ea - Font dell'Est asiatico del corpo (Font est-asiatico minore)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Questa classe viene utilizzata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che non viene applicata alcuna ereditarietà durante il recupero dei valori, quindi nella maggior parte dei casi otterrai valori che indicano "non definito".

Per ottenere i valori dei parametri di formattazione effettivi includendo quelli ereditati è necessario utilizzare il metodo [getEffective](../../com.aspose.slides/portionformat\#getEffective) che restituisce un'istanza [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inizializza una nuova istanza della classe [PortionFormat](../../com.aspose.slides/portionformat). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Restituisce o imposta l'identificatore del segnalibro. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Restituisce o imposta l'identificatore del segnalibro. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina se il smart tag deve essere pulito. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina se il smart tag deve essere pulito. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Restituisce o imposta l'iperlink definito per il clic del mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Restituisce o imposta l'iperlink definito per il clic del mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Restituisce o imposta l'iperlink definito per il passaggio del mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Restituisce o imposta l'iperlink definito per il passaggio del mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gestore degli iperlink. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Inizializza una nuova istanza della classe [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Restituisce o imposta l'identificatore del segnalibro. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Restituisce o imposta l'identificatore del segnalibro. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Determina se il smart tag deve essere pulito. Nessuna ereditarietà applicata. Lettura/scrittura boolean .

**Restituisce:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Determina se il smart tag deve essere pulito. Nessuna ereditarietà applicata. Lettura/scrittura boolean .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Restituisce o imposta l'iperlink definito per il clic del mouse. Lettura/scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Restituisce o imposta l'iperlink definito per il clic del mouse. Lettura/scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Restituisce o imposta l'iperlink definito per il passaggio del mouse. Lettura/scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Restituisce:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Restituisce o imposta l'iperlink definito per il passaggio del mouse. Lettura/scrittura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Gestore degli iperlink. Sola lettura [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Restituisce:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Un [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).