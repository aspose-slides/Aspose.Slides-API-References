---
title: SmartArtShape
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente une forme SmartArt
type: docs
url: /fr/com.aspose.slides/smartartshape/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISmartArtShape](../../com.aspose.slides/ismartartshape)  
```
public class SmartArtShape extends GeometryShape implements ISmartArtShape
```

Représente une forme SmartArt  

## Méthodes

| Méthode | Description |
| --- | --- |
| [getShapeType()](#getShapeType--) | Renvoie ou définit le type de préréglage de géométrie. |
| [setShapeType(int value)](#setShapeType-int-) | Renvoie ou définit le type de préréglage de géométrie. |
| [getTextFrame()](#getTextFrame--) | Renvoie le texte de la forme SmartArt. |

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Renvoie ou définit le type de préréglage de géométrie. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Retourne :**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Renvoie ou définit le type de préréglage de géométrie. Remarque : lors du changement de valeur, toutes les valeurs d'ajustement seront réinitialisées à leurs valeurs par défaut. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Renvoie le texte de la forme SmartArt. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Retourne :**  
[ITextFrame](../../com.aspose.slides/itextframe)