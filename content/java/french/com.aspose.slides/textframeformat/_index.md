---
title: TextFrameFormat
second_title: Référence API Aspose.Slides pour Java
description: Contient les propriétés formatTextFrameFormatting des TextFrames.
type: docs
url: /fr/com.aspose.slides/textframeformat/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Contient les propriétés formatTextFrameFormatting du TextFrame.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initialise une nouvelle instance de la classe [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Renvoie le style du texte. |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [getWrapText()](#getWrapText--) | Vrai si le texte est renvoyé aux marges du TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Vrai si le texte est renvoyé aux marges du TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Renvoie ou définit l'ancrage vertical du texte dans un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Renvoie ou définit l'ancrage vertical du texte dans un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [getTextVerticalType()](#getTextVerticalType--) | Détermine l'orientation du texte. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Détermine l'orientation du texte. |
| [getAutofitType()](#getAutofitType--) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [getColumnCount()](#getColumnCount--) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [setColumnCount(int value)](#setColumnCount-int-) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [getColumnSpacing()](#getColumnSpacing--) | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). |
| [getRotationAngle()](#getRotationAngle--) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |
| [getTransform()](#getTransform--) | Obtient ou définit la forme d'habillage du texte. |
| [setTransform(byte value)](#setTransform-byte-) | Obtient ou définit la forme d'habillage du texte. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Obtient ou définit le maintien du texte plat même si un effet de rotation 3-D a été appliqué. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Obtient ou définit le maintien du texte plat même si un effet de rotation 3-D a été appliqué. |
| [getEffective()](#getEffective--) | Obtient les données de formatage effectif du cadre de texte avec l'héritage appliqué. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initialise une nouvelle instance de la classe [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Renvoie le style du texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3d pour un texte. Lecture seule [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Définir la transformation du texte
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Définir l'extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Définir le contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Définir la profondeur
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Définir le matériau
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Définir l'éclairage
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Définir le type de caméra
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Renvoie ou définit l'ancrage vertical du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Renvoie :**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Renvoie ou définit l'ancrage vertical du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Renvoie :**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. La valeur 0 signifie valeur indéfinie. Lecture/écriture int.

--------------------

> ```
> Le code d'exemple suivant montre comment ajouter une colonne dans le cadre de texte d'une présentation PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. La valeur 0 signifie valeur indéfinie. Lecture/écriture int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne s'applique que lorsqu'il y a plus d'une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. Lecture/écriture double.

**Renvoie :**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Renvoie ou définit l'espace entre les colonnes de texte dans la zone de texte (en points). Cela ne s'applique que lorsqu'il y a plus d'une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera réglée à zéro. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. 
>  En plus de cela, le corps du texte lui--même a une rotation de -90 degrés dans le sens inverse des aiguilles d'une montre appliquée. 
>  Alors la forme résultante semblerait être tournée mais le texte à l'intérieur semblerait ne pas avoir du tout été tourné.
```

**Renvoie :**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. 
>  En plus de cela, le corps du texte lui-même a une rotation de -90 degrés 
>  dans le sens inverse des aiguilles d'une montre appliquée. Alors la forme résultante semblerait
>  être tournée mais le texte à l'intérieur semblerait ne pas avoir été tourné du tout.
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Obtient ou définit la forme d'habillage du texte. Lecture/écriture [TextShapeType](../../com.aspose.slides/textshapetype).

**Renvoie :**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Obtient ou définit la forme d'habillage du texte. Lecture/écriture [TextShapeType](../../com.aspose.slides/textshapetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Obtient ou définit le maintien du texte plat même si un effet de rotation 3-D a été appliqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public  



```

Obtient ou définit le maintien du texte plat même si un effet de rotation 3-D a été appliqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Obtient les données de formatage effectif du cadre de texte avec l'héritage appliqué.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - Un [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).