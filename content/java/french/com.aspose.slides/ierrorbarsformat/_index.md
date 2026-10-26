---
title: IErrorBarsFormat
second_title: Référence API Aspose.Slides pour Java
description: Représente les barres d'erreur d'une série de graphique.
type: docs
url: /fr/com.aspose.slides/ierrorbarsformat/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Représente les barres d’erreur d’une série de graphique. Les valeurs personnalisées d’ErrorBars se trouvent dans IChartDataPointCollection (dans la propriété [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient ou définit le type des barres d’erreur. |
| [setType(int value)](#setType-int-) | Obtient ou définit le type des barres d’erreur. |
| [getValueType()](#getValueType--) | Représente les façons possibles de déterminer la longueur des barres d’erreur. |
| [setValueType(int value)](#setValueType-int-) | Représente les façons possibles de déterminer la longueur des barres d’erreur. |
| [hasEndCap()](#hasEndCap--) | Spécifie qu’une coiffe de fin n’est pas dessinée sur les barres d’erreur. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Spécifie qu’une coiffe de fin n’est pas dessinée sur les barres d’erreur. |
| [getValue()](#getValue--) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d’erreur. |
| [setValue(float value)](#setValue-float-) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d’erreur. |
| [getFormat()](#getFormat--) | Représente le format des barres d’erreur. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente le format des barres d’erreur. |
| [isVisible()](#isVisible--) | Obtient ou définit la visibilité des barres d’erreur. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit la visibilité des barres d’erreur. |

### getType() {#getType--}
```
public abstract int getType()
```

Obtient ou définit le type des barres d’erreur. Lecture/écriture [ErrorBarType](../../com.aspose.slides/errorbartype).

**Renvoie :**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Obtient ou définit le type des barres d’erreur. Lecture/écriture [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Représente les façons possibles de déterminer la longueur des barres d’erreur. Dans le cas d’un type de valeur personnalisé, utilisez la propriété [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) du point de données spécifique dans la collection DataPoints de la série. Lecture/écriture [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Renvoie :**  
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Représente les façons possibles de déterminer la longueur des barres d’erreur. Dans le cas d’un type de valeur personnalisé, utilisez la propriété [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) du point de données spécifique dans la collection DataPoints de la série. Lecture/écriture [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Spécifie qu’une coiffe de fin n’est pas dessinée sur les barres d’erreur. Lecture/écriture boolean.

**Renvoie :**  
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Spécifie qu’une coiffe de fin n’est pas dessinée sur les barres d’erreur. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d’erreur. Lecture/écriture float.

**Renvoie :**  
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d’erreur. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Représente le format des barres d’erreur. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**  
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Représente le format des barres d’erreur. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Obtient ou définit la visibilité des barres d’erreur. Lecture/écriture boolean.

**Renvoie :**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Obtient ou définit la visibilité des barres d’erreur. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |