---
title: ErrorBarsFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les barres d'erreur d'une série de graphique.
type: docs
url: /fr/com.aspose.slides/errorbarsformat/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Représente les barres d'erreur d'une série de graphique. Les valeurs personnalisées d'ErrorBars sont dans IChartDataPointCollection (dans la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Obtient ou définit le type des barres d'erreur. |
| [setType(int value)](#setType-int-) | Obtient ou définit le type des barres d'erreur. |
| [getValueType()](#getValueType--) | Représente les façons possibles de déterminer la longueur des barres d'erreur. |
| [setValueType(int value)](#setValueType-int-) | Représente les façons possibles de déterminer la longueur des barres d'erreur. |
| [hasEndCap()](#hasEndCap--) | Spécifie qu'une coiffe finale n'est pas dessinée sur les barres d'erreur. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Spécifie qu'une coiffe finale n'est pas dessinée sur les barres d'erreur. |
| [getValue()](#getValue--) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. |
| [setValue(float value)](#setValue-float-) | Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. |
| [getFormat()](#getFormat--) | Représente le format des barres d'erreur. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente le format des barres d'erreur. |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [isVisible()](#isVisible--) | Obtient ou définit la visibilité des barres d'erreur. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit la visibilité des barres d'erreur. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Obtient ou définit le type des barres d'erreur. Lecture/écriture [ErrorBarType](../../com.aspose.slides/errorbartype).

**Renvoie :**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Obtient ou définit le type des barres d'erreur. Lecture/écriture [ErrorBarType](../../com.aspose.slides/errorbartype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Représente les façons possibles de déterminer la longueur des barres d'erreur. Dans le cas d'un type de valeur personnalisé, utilisez la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) du point de données spécifique dans la collection DataPoints de la série. Dans le cas des types de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur. Lecture/écriture [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Renvoie :**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Représente les façons possibles de déterminer la longueur des barres d'erreur. Dans le cas d'un type de valeur personnalisé, utilisez la propriété ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) du point de données spécifique dans la collection DataPoints de la série. Dans le cas des types de valeur Fixed, Percentage ou StandardDeviation, utilisez la propriété Value pour spécifier la valeur. Lecture/écriture [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Spécifie qu'une coiffe finale n'est pas dessinée sur les barres d'erreur. Lecture/écriture booléen.

**Renvoie :**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Spécifie qu'une coiffe finale n'est pas dessinée sur les barres d'erreur. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renvoie NaN. Lecture/écriture float.

**Renvoie :**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Obtient ou définit la valeur utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Dans tout autre cas, renvoie NaN. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Représente le format des barres d'erreur. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Représente le format des barres d'erreur. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Obtient ou définit la visibilité des barres d'erreur. Lecture/écriture booléen.

**Renvoie :**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Obtient ou définit la visibilité des barres d'erreur. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente d'un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d'un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)