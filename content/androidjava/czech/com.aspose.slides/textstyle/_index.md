---
title: TextStyle
second_title: Aspose.Slides pro Android přes Java API Reference
description: Tato třída obsahuje vlastnosti formátování textového stylu.
type: docs
url: /cs/com.aspose.slides/textstyle/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Tato třída obsahuje vlastnosti formátování textových stylů.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Pokud existuje úroveň stylu, vrátí ji, jinak vrátí null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Výchozí vlastnosti odstavce. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování textového stylu s aplikovanou dědičností. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verze. Pouze ke čtení long.

**Vrací:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Pokud existuje úroveň stylu, vrátí ji, jinak vrátí null.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index úrovně počítaný od nuly. Musí být v intervalu 0..8. |

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formátování úrovně [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Výchozí vlastnosti odstavce. Pouze ke čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Získá efektivní data formátování textového stylu s aplikovanou dědičností.

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


**Vrací:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - je [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).