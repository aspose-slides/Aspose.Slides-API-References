---
title: IAdjustValue
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une valeur d'ajustement d'une forme géométrique.
type: docs
url: /fr/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Représente une valeur d'ajustement d'une forme géométrique. Ces valeurs affectent la forme.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | Renvoie ou définit la valeur d'ajustement telle quelle. |
| [setRawValue(long value)](#setRawValue-long-) | Renvoie ou définit la valeur d'ajustement telle quelle. |
| [getAngleValue()](#getAngleValue--) | Renvoie ou définit la valeur, en l'interprétant comme un angle en degrés. |
| [setAngleValue(float value)](#setAngleValue-float-) | Renvoie ou définit la valeur, en l'interprétant comme un angle en degrés. |
| [getName()](#getName--) | Renvoie le nom de cette valeur d'ajustement. |
| [getType()](#getType--) | Renvoie le type de l'ajustement de forme. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Renvoie ou définit la valeur d'ajustement telle quelle. Lecture/écriture long.

**Renvoie :**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Renvoie ou définit la valeur d'ajustement telle quelle. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Renvoie ou définit la valeur, en l'interprétant comme un angle en degrés. Lecture/écriture float.

**Renvoie :**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Renvoie ou définit la valeur, en l'interprétant comme un angle en degrés. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```


Renvoie le nom de cette valeur d'ajustement. Lecture seule String.

**Renvoie :**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Renvoie le type de l'ajustement de forme. Lecture seule [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Renvoie :**
int