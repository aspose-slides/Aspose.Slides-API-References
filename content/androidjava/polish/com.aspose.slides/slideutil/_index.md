---
title: SlideUtil
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Udostępnia metody, które pomagają wyszukiwać kształty i tekst w prezentacji.
type: docs
url: /pl/com.aspose.slides/slideutil/
---
**Dziedziczenie:**
java.lang.Object
```
public class SlideUtil
```

Oferuje metody, które pomagają wyszukiwać kształty i tekst w prezentacji.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Znajduje kształt po alternatywnym tekście w prezentacji PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Znajduje kształt po alternatywnym tekście na slajdzie w prezentacji PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Wyszukuje wszystkie kształty na określonym slajdzie, które pasują do podanego typu placeholdera. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Zmienia położenie wszystkich kształtów na slajdzie. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Zmienia położenie wybranych kształtów na slajdzie. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Zmienia położenie wszystkich kształtów w grupie kształtów. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Zmienia położenie wybranych kształtów w grupie kształtów. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Wyszukuje i zamienia tekst w prezentacji przy użyciu podanego formatu |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Wyszukuje i zamienia tekst w prezentacji przy użyciu podanego formatu |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Zwraca wszystkie ramki tekstowe na slajdzie w prezentacji PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Zwraca wszystkie ramki tekstowe na określonym slajdzie, które zawierają podany tekst. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Zwraca wszystkie ramki tekstowe w prezentacji PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Konwertuje format pliku źródłowego na odpowiadający [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Znajduje kształt po alternatywnym tekście w prezentacji PPTX.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Skanowana prezentacja. |
| altText | java.lang.String | Tekst alternatywny kształtu. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Kształt lub null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Znajduje kształt po alternatywnym tekście na slajdzie w prezentacji PPTX.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Skanowany slajd. |
| altText | java.lang.String | Tekst alternatywny kształtu. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Kształt lub null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Wyszukuje wszystkie kształty na określonym slajdzie, które pasują do podanego typu placeholdera.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slajd, na którym wyszukiwane są kształty. |
| placeholderType | byte | Typ placeholdera, którym filtrowane są kształty. |

**Zwraca:**
com.aspose.slides.IShape[] - Tablica obiektów [IShape](../../com.aspose.slides/ishape) pasujących do określonego typu placeholdera.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Zmienia położenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | int | Określa, jaki typ wyrównania zostanie zastosowany. |
| alignToSlide | boolean | Jeśli true, kształty będą wyrównane względem krawędzi slajdu. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slajd nadrzędny. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Zmienia położenie wybranych kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | int | Określa, jaki typ wyrównania zostanie zastosowany. |
| alignToSlide | boolean | Jeśli true, kształty będą wyrównane względem krawędzi slajdu. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slajd nadrzędny. |
| shapeIndexes | int[] | Indeksy kształtów do wyrównania. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Zmienia położenie wszystkich kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | int | Określa, jaki typ wyrównania zostanie zastosowany. |
| alignToSlide | boolean | Jeśli true, kształty będą wyrównane względem krawędzi slajdu. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupa kształtów nadrzędna. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Zmienia położenie wybranych kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alignmentType | int | Określa, jaki typ wyrównania zostanie zastosowany. |
| alignToSlide | boolean | Jeśli true, kształty będą wyrównane względem krawędzi slajdu. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupa kształtów nadrzędna. |
| shapeIndexes | int[] | Indeksy kształtów do wyrównania. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Wyszukuje i zamienia tekst w prezentacji.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Skanowana prezentacja. |
| withMasters | boolean | Określa, czy należy skanować slajdy master. |
| find | java.lang.String | Wartość ciągu do znalezienia. |
| replace | java.lang.String | Wartość ciągu do zamiany. znak znalezionego ciągu |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Wyszukuje i zamienia tekst w prezentacji przy użyciu podanego formatu.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Skanowana prezentacja. |
| withMasters | boolean | Określa, czy należy skanować slajdy master. |
| find | java.lang.String | Wartość ciągu do znalezienia. |
| replace | java.lang.String | Wartość ciągu do zamiany. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format zastępowanej części tekstu. Jeśli null, zostanie użyty format pierwszego znaku znalezionego ciągu. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Zwraca wszystkie ramki tekstowe na slajdzie w prezentacji PPTX.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Skanowany slajd. |

**Zwraca:**
com.aspose.slides.ITextFrame[] - Tablica obiektów [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Zwraca wszystkie ramki tekstowe na określonym slajdzie, które zawierają podany tekst.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slajd do przeszukania. |
| text | java.lang.String | Tekst, którego należy szukać w ramach tekstowych. |
| checkPlaceholderText | boolean | Określa, czy uwzględniać ramki tekstowe, które są puste, ale ich tekst placeholdera zawiera szukany tekst. |

**Zwraca:**
com.aspose.slides.ITextFrame[] - Tablica obiektów [ITextFrame](../../com.aspose.slides/itextframe) zawierających określony tekst.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Zwraca wszystkie ramki tekstowe w prezentacji PPTX.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Skanowana prezentacja. |
| withMasters | boolean | Określa, czy należy skanować slajdy master. |

**Zwraca:**
com.aspose.slides.ITextFrame[] - Tablica obiektów [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Konwertuje format pliku źródłowego na odpowiadający [SaveFormat](../../com.aspose.slides/saveformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| format | int | Format pliku źródłowego. |

**Zwraca:**
int - Odpowiednia wartość [SaveFormat](../../com.aspose.slides/saveformat).