---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contient les propriétés de mise en forme des TextFrames.
type: docs
url: /fr/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Contient les propriétés de mise en forme du TextFrame.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Renvoie le style du texte. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [getWrapText()](#getWrapText--) | Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Renvoie ou définit l'ancre verticale du texte dans un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Renvoie ou définit l'ancre verticale du texte dans un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [getTextVerticalType()](#getTextVerticalType--) | Détermine l'orientation du texte. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Détermine l'orientation du texte. |
| [getAutofitType()](#getAutofitType--) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [getColumnCount()](#getColumnCount--) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [setColumnCount(int value)](#setColumnCount-int-) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [getColumnSpacing()](#getColumnSpacing--) | Renvoie ou définit l'espacement entre les colonnes de texte dans la zone de texte (en points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Renvoie ou définit l'espacement entre les colonnes de texte dans la zone de texte (en points). |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Renvoie ou définit le maintien du texte hors de la scène 3D entièrement. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Renvoie ou définit le maintien du texte hors de la scène 3D entièrement. |
| [getRotationAngle()](#getRotationAngle--) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |
| [getTransform()](#getTransform--) | Obtient ou définit la forme d'habillage du texte. |
| [setTransform(byte value)](#setTransform-byte-) | Obtient ou définit la forme d'habillage du texte. |
| [getEffective()](#getEffective--) | Obtient les données de formatage du cadre de texte effectives avec l'héritage appliqué. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Renvoie le style du texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourne :**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Retourne :**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Retourne :**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Retourne :**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Retourne :**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne :**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Renvoie ou définit l'ancre verticale du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourne :**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Renvoie ou définit l'ancre verticale du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne :**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourne :**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retourne :**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Renvoie ou définit le mode d'ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. La valeur 0 signifie une valeur indéfinie. Lecture/écriture int.

**Retourne :**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. La valeur 0 signifie une valeur indéfinie. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Renvoie ou définit l'espacement entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s'appliquer que lorsqu'il y a plus d'une colonne présente. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. Lecture/écriture double.

**Retourne :**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Renvoie ou définit l'espacement entre les colonnes de texte dans la zone de texte (en points). Cela ne doit s'appliquer que lorsqu'il y a plus d'une colonne présente. Cette valeur doit être un nombre positif. Sinon, la valeur sera définie à zéro. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D pour un texte. Lecture seule [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Définir la transformation du texte
>      // Définir l'extrusion
>      // Définir le contour
>      // Définir la profondeur
>      // Définir le matériau
>      // Définir l'éclairage
>      // Définir le type de caméra
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Returns or set keeping text out of 3D scene entirely. Read/write boolean.

**Returns:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Returns or set keeping text out of 3D scene entirely. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Returns:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, alors elle est appliquée indépendamment de la forme. Autrement dit, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte est résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. 
>  En plus de cela, le corps du texte lui-même a une rotation de -90 degrés dans le sens inverse des aiguilles d'une montre appliquée. Alors la forme résultante semblerait être
>  tournée mais le texte à l'intérieur semblerait ne pas avoir été tourné du tout.
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Obtient ou définit la forme d'habillage du texte. Lecture/écriture [TextShapeType](../../com.aspose.slides/textshapetype).

**Retourne :**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Gets or sets text wrapping shape. Read/write [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()


Obtient les données de formatage du cadre de texte effectives avec l'héritage appliqué.

**Retourne :**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).