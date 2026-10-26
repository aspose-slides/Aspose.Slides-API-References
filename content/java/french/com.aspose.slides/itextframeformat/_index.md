---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Contains the TextFrames formatting properties.
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
| [getWrapText()](#getWrapText--) | Vrai si le texte est renvoyé aux marges du TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Vrai si le texte est renvoyé aux marges du TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Renvoie ou définit l’ancrage vertical du texte dans un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Renvoie ou définit l’ancrage vertical du texte dans un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. |
| [getTextVerticalType()](#getTextVerticalType--) | Détermine l’orientation du texte. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Détermine l’orientation du texte. |
| [getAutofitType()](#getAutofitType--) | Renvoie ou définit le mode d’ajustement automatique du texte. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Renvoie ou définit le mode d’ajustement automatique du texte. |
| [getColumnCount()](#getColumnCount--) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [setColumnCount(int value)](#setColumnCount-int-) | Renvoie ou définit le nombre de colonnes dans la zone de texte. |
| [getColumnSpacing()](#getColumnSpacing--) | Renvoie ou définit l’espacement entre les colonnes de texte dans la zone de texte (en points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Renvoie ou définit l’espacement entre les colonnes de texte dans la zone de texte (en points). |
| [getThreeDFormat()](#getThreeDFormat--) | Renvoie l’objet ThreeDFormat qui représente les propriétés d’effet 3d pour un texte. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Renvoie ou définit le texte hors de la scène 3D entièrement. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Renvoie ou définit le texte hors de la scène 3D entièrement. |
| [getRotationAngle()](#getRotationAngle--) | Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. |
| [getTransform()](#getTransform--) | Obtient ou définit la forme d’enveloppe du texte. |
| [setTransform(byte value)](#setTransform-byte-) | Obtient ou définit la forme d’enveloppe du texte. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme effectives du cadre de texte avec l’héritage appliqué. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Renvoie le style du texte. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Valeur de retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Valeur de retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Valeur de retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Valeur de retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Valeur de retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Valeur de retour:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Vrai si le texte est renvoyé aux marges du TextFrame. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Renvoie ou définit l’ancrage vertical du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Valeur de retour:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Renvoie ou définit l’ancrage vertical du texte dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Valeur de retour:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Si NullableBool.True alors le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Détermine l’orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l’angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Valeur de retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Détermine l’orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l’angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Renvoie ou définit le mode d’ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Valeur de retour:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Renvoie ou définit le mode d’ajustement automatique du texte. Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. La valeur 0 signifie une valeur indéfinie. Lecture/écriture int.

**Valeur de retour:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Renvoie ou définit le nombre de colonnes dans la zone de texte. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. La valeur 0 signifie une valeur indéfinie. Lecture/écriture int.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Renvoie ou définit l’espacement entre les colonnes de texte dans la zone de texte (en points). Cela ne s’applique que lorsqu’il y a plus d’une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. Lecture/écriture double.

**Valeur de retour:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Renvoie ou définit l’espacement entre les colonnes de texte dans la zone de texte (en points). Cela ne s’applique que lorsqu’il y a plus d’une colonne. Cette valeur doit être un nombre positif. Sinon, la valeur sera fixée à zéro. Lecture/écriture double.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Renvoie l’objet ThreeDFormat qui représente les propriétés d’effet 3d pour un texte. Lecture seule [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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


**Valeur de retour:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Renvoie ou définit le texte hors de la scène 3D entièrement. Lecture/écriture boolean.

**Valeur de retour:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Renvoie ou définit le texte hors de la scène 3D entièrement. Lecture/écriture boolean.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. 
>  En plus de cela, le corps du texte lui-même a une rotation de -90 degrés 
>  dans le sens inverse des aiguilles d'une montre appliquée. Ensuite, la forme résultante semblerait 
>  être tournée mais le texte à l'intérieur semblerait n'avoir pas du tout été tourné.
```

**Valeur de retour:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte, résumée à partir de cette propriété et du type vertical prédéfini dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée. 
>  En plus de cela, le corps du texte lui-même a une rotation de -90 degrés 
>  dans le sens inverse des aiguilles d'une montre appliquée. Alors la forme résultante semblerait 
>  être tournée mais le texte à l'intérieur semblerait ne pas avoir du tout été tourné.
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Obtient ou définit la forme d’enveloppe du texte. Lecture/écriture [TextShapeType](../../com.aspose.slides/textshapetype).

**Valeur de retour:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Obtient ou définit la forme d’enveloppe du texte. Lecture/écriture [TextShapeType](../../com.aspose.slides/textshapetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Obtient les données de mise en forme effectives du cadre de texte avec l’héritage appliqué.

**Valeur de retour:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).