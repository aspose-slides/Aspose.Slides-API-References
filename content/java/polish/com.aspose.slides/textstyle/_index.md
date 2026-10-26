---
title: TextStyle
second_title: Aspose.Slides dla Java - odniesienie API
description: Ta klasa zawiera właściwości formatowania stylu tekstu.
type: docs
url: /pl/com.aspose.slides/textstyle/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Ta klasa zawiera właściwości formatowania stylu tekstu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Jeśli poziom stylu istnieje, zwraca go, w przeciwnym razie zwraca null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Domyślne właściwości akapitu. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania stylu tekstu z zastosowaną dziedzicznością. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu, long.

**Zwraca:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Jeśli poziom stylu istnieje, zwraca go, w przeciwnym razie zwraca null.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks poziomu rozpoczynający się od zera. Musi mieścić się w przedziale 0..8. |

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatowanie poziomu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Domyślne właściwości akapitu. Tylko do odczytu [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Zwraca:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Pobiera efektywne dane formatowania stylu tekstu z zastosowaną dziedzicznością.

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

**Zwraca:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Obiekt [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).