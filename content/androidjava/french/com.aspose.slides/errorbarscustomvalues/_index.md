---
title: ErrorBarsCustomValues
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Spécifie les valeurs de la barre d'erreur.
type: docs
url: /fr/com.aspose.slides/errorbarscustomvalues/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Spécifie les valeurs de la barre d'erreur. Elle ne doit être utilisée que lorsque le type de valeur des barres d'erreur est Custom.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Spécifie la valeur de la barre d'erreur dans la direction négative. |
| [getYMinus()](#getYMinus--) | Spécifie la valeur de la barre d'erreur dans la direction négative. |
| [getXPlus()](#getXPlus--) | Spécifie la valeur de la barre d'erreur dans la direction positive. |
| [getYPlus()](#getYPlus--) | Spécifie la valeur de la barre d'erreur dans la direction positive. |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```


Spécifie la valeur de la barre d'erreur dans la direction négative. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsXFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```


Spécifie la valeur de la barre d'erreur dans la direction négative. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsYFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```


Spécifie la valeur de la barre d'erreur dans la direction positive. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsXFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```


Spécifie la valeur de la barre d'erreur dans la direction positive. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsYFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)