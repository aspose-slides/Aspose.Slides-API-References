---
title: TextStyle
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Questa classe contiene le proprietà di formattazione dello stile del testo.
type: docs
url: /it/com.aspose.slides/textstyle/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Questa classe contiene le proprietà di formattazione dello stile del testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Se il livello di stile esiste restituisce il valore, altrimenti restituisce null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Proprietà predefinite del paragrafo. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione dello stile del testo efficace con l'ereditarietà applicata. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Long di sola lettura.

**Restituisce:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Se il livello di stile esiste restituisce il valore, altrimenti restituisce null.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice basato su zero del livello. Deve trovarsi nell'intervallo 0..8. |

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formattazione del livello [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Proprietà predefinite del paragrafo. [IParagraphFormat](../../com.aspose.slides/iparagraphformat) di sola lettura.

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Ottiene i dati di formattazione dello stile del testo efficace con l'ereditarietà applicata.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Un [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).