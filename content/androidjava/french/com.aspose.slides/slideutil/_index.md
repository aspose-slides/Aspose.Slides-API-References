---
title: SlideUtil
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Propose des méthodes qui aident à rechercher des formes et du texte dans une présentation.
type: docs
url: /fr/com.aspose.slides/slideutil/
---
**Héritage :**
java.lang.Object
```
public class SlideUtil
```

Propose des méthodes qui aident à rechercher des formes et du texte dans une présentation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Trouve une forme par texte alternatif dans une présentation PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Trouve une forme par texte alternatif sur une diapositive dans une présentation PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Recherche toutes les formes sur la diapositive spécifiée qui correspondent au type d'espace réservé donné. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Modifie le placement de toutes les formes sur la diapositive. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Modifie le placement des formes sélectionnées sur la diapositive. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Modifie le placement de toutes les formes au sein d'un groupe de formes. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Modifie le placement des formes sélectionnées au sein d'un groupe de formes. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Recherche et remplace le texte dans la présentation avec le format donné |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Recherche et remplace le texte dans la présentation avec le format donné |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Renvoie toutes les cadres de texte sur une diapositive dans une présentation PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Renvoie toutes les cadres de texte sur la diapositive spécifiée qui contiennent le texte donné. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Renvoie toutes les cadres de texte dans une présentation PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Convertit un format de fichier source en le [SaveFormat](../../com.aspose.slides/saveformat) correspondant. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Trouve une forme par texte alternatif dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation analysée. |
| altText | java.lang.String | Texte alternatif d'une forme. |

**Renvoie :**
[IShape](../../com.aspose.slides/ishape) - Shape ou null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Trouve une forme par texte alternatif sur une diapositive dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive analysée. |
| altText | java.lang.String | Texte alternatif d'une forme. |

**Renvoie :**
[IShape](../../com.aspose.slides/ishape) - Shape ou null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Recherche toutes les formes sur la diapositive spécifiée qui correspondent au type d'espace réservé donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositive où rechercher les formes. |
| placeholderType | byte | Le type d'espace réservé pour filtrer les formes. |

**Renvoie :**
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape) qui correspondent au type d'espace réservé spécifié.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```
Finds and replaces text in presentation with given format

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. character of the found string |
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```
Finds and replaces text in presentation with given format

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format for replacing text portion. If null then will be used format of the first character of the found string |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Returns all text frames on a slide in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Scanned slide. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Returns all text frames on the specified slide that contain the given text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The slide to search. |
| text | java.lang.String | The text to search for within text frames. |
| checkPlaceholderText | boolean | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |

**Returns:**
com.aspose.slides.ITextFrame[] - An array of [ITextFrame](../../com.aspose.slides/itextframe) objects that contain the specified text.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Returns all text frames in a PPTX presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |

**Returns:**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)


Convertit un format de fichier source en le [SaveFormat](../../com.aspose.slides/saveformat) correspondant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | int | Le format de fichier source. |

**Renvoie :**
int - La valeur [SaveFormat](../../com.aspose.slides/saveformat) correspondante.