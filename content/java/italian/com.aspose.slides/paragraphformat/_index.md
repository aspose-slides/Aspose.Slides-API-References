---
title: ParagraphFormat
second_title: Riferimento API Aspose.Slides per Java
description: Questa classe contiene le proprietà di formattazione del paragrafo.
type: docs
url: /it/com.aspose.slides/paragraphformat/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

--------------------

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che non viene applicata alcuna ereditarietà quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che significano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione inclusa l'ereditarietà, è necessario utilizzare il metodo [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) che restituisce un'istanza di [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Inizializza una nuova istanza della classe [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBullet()](#getBullet--) | Restituisce il formato del punto elenco del paragrafo. |
| [getDepth()](#getDepth--) | Restituisce o imposta la profondità del paragrafo. |
| [setDepth(short value)](#setDepth-short-) | Restituisce o imposta la profondità del paragrafo. |
| [getAlignment()](#getAlignment--) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. |
| [setAlignment(int value)](#setAlignment-int-) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. |
| [getSpaceWithin()](#getSpaceWithin--) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. |
| [getSpaceBefore()](#getSpaceBefore--) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. |
| [getSpaceAfter()](#getSpaceAfter--) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Determina se l'interruzione di riga dell'Estremo orientale è usata in un paragrafo. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Determina se l'interruzione di riga dell'Estremo orientale è usata in un paragrafo. |
| [getRightToLeft()](#getRightToLeft--) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Determina se l'interruzione di riga latina è usata in un paragrafo. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Determina se l'interruzione di riga latina è usata in un paragrafo. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Determina se la punteggiatura penzolante è usata in un paragrafo. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Determina se la punteggiatura penzolante è usata in un paragrafo. |
| [getMarginLeft()](#getMarginLeft--) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. |
| [getMarginRight()](#getMarginRight--) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. |
| [setMarginRight(float value)](#setMarginRight-float-) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. |
| [getIndent()](#getIndent--) | Restituisce o imposta l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. |
| [setIndent(float value)](#setIndent-float-) | Restituisce o imposta l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Restituisce o imposta la dimensione della tabulazione predefinita senza ereditarietà. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Restituisce o imposta la dimensione della tabulazione predefinita senza ereditarietà. |
| [getTabs()](#getTabs--) | Restituisce le tabulazioni di un paragrafo. |
| [getFontAlignment()](#getFontAlignment--) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Restituisce il formato della porzione predefinita di un paragrafo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


Inizializza una nuova istanza della classe [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


Restituisce il formato del punto elenco del paragrafo. Sola lettura [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Restituisce:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


Restituisce o imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Lettura/scrittura short .

**Restituisce:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


Restituisce o imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Lettura/scrittura short .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanzia un oggetto Presentation che rappresenta un file PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accesso alla prima diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accesso al primo e al secondo segnaposto nella diapositiva e casting al tipo AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifica il testo in entrambi i segnaposto
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Recupero del primo paragrafo dei segnaposto
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Allineamento del paragrafo di testo al centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //Scrittura della presentazione come file PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanzia un oggetto Presentation che rappresenta un file PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Accesso alla prima diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accesso al primo e al secondo segnaposto nella diapositiva e casting al tipo AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Modifica il testo in entrambi i segnaposto
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Recupero del primo paragrafo dei segnaposto
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Allineamento del paragrafo di testo al centro
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Scrittura della presentazione come file PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, un valore negativo indica dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura float .

**Restituisce:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, un valore negativo indica dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float .

**Restituisce:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float .

**Restituisce:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco dovrebbe occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


Determina se l'interruzione di riga dell'Estremo orientale è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


Determina se l'interruzione di riga dell'Estremo orientale è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


Determina se l'interruzione di riga latina è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


Determina se l'interruzione di riga latina è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


Determina se la punteggiatura penzolante è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Restituisce:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


Determina se la punteggiatura penzolante è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [NullableBool](../../com.aspose.slides/nullablebool).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura float .

**Restituisce:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura float .

**Restituisce:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


Restituisce o imposta l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. L'indentazione pendente può essere definita con valori negativi. Lettura/scrittura float .

**Restituisce:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


Restituisce o imposta l'indentazione della prima riga/pendente del paragrafo senza ereditarietà. L'indentazione pendente può essere definita con valori negativi. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


Restituisce o imposta la dimensione della tabulazione predefinita senza ereditarietà. Lettura/scrittura float .

**Restituisce:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


Restituisce o imposta la dimensione della tabulazione predefinita senza ereditarietà. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [ITabCollection](../../com.aspose.slides/itabcollection).

**Restituisce:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Restituisce:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Lettura/scrittura [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


Restituisce il formato della porzione predefinita di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [IPortionFormat](../../com.aspose.slides/iportionformat).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Un [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Sola lettura long.

**Restituisce:**
long