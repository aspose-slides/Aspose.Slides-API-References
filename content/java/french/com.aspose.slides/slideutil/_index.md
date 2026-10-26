---
title: SlideUtil
second_title: Référence API Aspose.Slides pour Java
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
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Trouve la forme par texte alternatif dans une présentation PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Trouve la forme par texte alternatif sur une diapositive dans une présentation PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Recherche toutes les formes sur la diapositive spécifiée qui correspondent au type d’espace réservé donné. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Modifie le placement de toutes les formes sur la diapositive. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Modifie le placement des formes sélectionnées sur la diapositive. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Modifie le placement de toutes les formes au sein d’un groupe de formes. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Modifie le placement des formes sélectionnées au sein d’un groupe de formes. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Recherche et remplace le texte dans la présentation avec le format donné |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Recherche et remplace le texte dans la présentation avec le format donné |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Renvoie tous les cadres de texte sur une diapositive dans une présentation PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Renvoie tous les cadres de texte sur la diapositive spécifiée qui contiennent le texte donné. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Renvoie tous les cadres de texte dans une présentation PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Convertit un format de fichier source en le [SaveFormat](../../com.aspose.slides/saveformat) correspondant. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Trouve la forme par texte alternatif dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation analysée. |
| altText | java.lang.String | Texte alternatif d’une forme. |

**Retour :**
[IShape](../../com.aspose.slides/ishape) - Shape ou null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Trouve la forme par texte alternatif sur une diapositive dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive analysée. |
| altText | java.lang.String | Texte alternatif d’une forme. |

**Retour :**
[IShape](../../com.aspose.slides/ishape) - Shape ou null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Recherche toutes les formes sur la diapositive spécifiée qui correspondent au type d’espace réservé donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositive où rechercher des formes. |
| placeholderType | byte | Le type d’espace réservé pour filtrer les formes. |

**Retour :**
com.aspose.slides.IShape[] - Un tableau d'objets [IShape](../../com.aspose.slides/ishape) qui correspondent au type d’espace réservé spécifié.
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | int | Détermine le type d’alignement qui sera appliqué. |
| alignToSlide | boolean | Si true, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive parente. |
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Modifie le placement des formes sélectionnées sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | int | Détermine le type d’alignement qui sera appliqué. |
| alignToSlide | boolean | Si true, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive parente. |
| shapeIndexes | int[] | Index des formes à aligner. |
### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Modifie le placement de toutes les formes au sein d’un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | int | Détermine le type d’alignement qui sera appliqué. |
| alignToSlide | boolean | Si true, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Groupe de formes parent. |
### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Modifie le placement des formes sélectionnées au sein d’un groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | int | Détermine le type d’alignement qui sera appliqué. |
| alignToSlide | boolean | Si true, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Groupe de formes parent. |
| shapeIndexes | int[] | Index des formes à aligner. |
### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Recherche et remplace le texte dans la présentation avec le format donné

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation analysée. |
| withMasters | boolean | Détermine si les diapositives maîtres doivent être analysées. |
| find | java.lang.String | Valeur de chaîne à rechercher. |
| replace | java.lang.String | Valeur de chaîne à remplacer. Caractère de la chaîne trouvée |
### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Recherche et remplace le texte dans la présentation avec le format donné

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation analysée. |
| withMasters | boolean | Détermine si les diapositives maîtres doivent être analysées. |
| find | java.lang.String | Valeur de chaîne à rechercher. |
| replace | java.lang.String | Valeur de chaîne à remplacer. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format pour remplacer la portion de texte. Si null, le format du premier caractère de la chaîne trouvée sera utilisé. |
### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Renvoie tous les cadres de texte sur une diapositive dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive analysée. |

**Retour :**
com.aspose.slides.ITextFrame[] - Tableau d'objets [TextFrame](../../com.aspose.slides/textframe).
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Renvoie tous les cadres de texte sur la diapositive spécifiée qui contiennent le texte donné.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositive à rechercher. |
| text | java.lang.String | Le texte à rechercher dans les cadres de texte. |
| checkPlaceholderText | boolean | Indique s’il faut inclure les cadres de texte vides dont le texte d’espace réservé contient le texte recherché. |

**Retour :**
com.aspose.slides.ITextFrame[] - Un tableau d'objets [ITextFrame](../../com.aspose.slides/itextframe) qui contiennent le texte spécifié.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Renvoie tous les cadres de texte dans une présentation PPTX.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Présentation analysée. |
| withMasters | boolean | Détermine si les diapositives maîtres doivent être analysées. |

**Retour :**
com.aspose.slides.ITextFrame[] - Tableau d'objets [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Convertit un format de fichier source en le [SaveFormat](../../com.aspose.slides/saveformat) correspondant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | int | Le format de fichier source. |

**Retour :**
int - La valeur [SaveFormat](../../com.aspose.slides/saveformat) correspondante.