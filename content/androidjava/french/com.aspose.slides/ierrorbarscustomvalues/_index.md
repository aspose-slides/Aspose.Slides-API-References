---
title: IErrorBarsCustomValues
second_title: Aspose.Slides pour Android via Référence de l'API Java
description: Spécifie les valeurs des barres d'erreur.
type: docs
url: /fr/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Spécifie les valeurs des barres d'erreur. Elle doit être utilisée uniquement lorsque le type de valeur des barres d'erreur est Custom.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXMinus()](#getXMinus--) | Spécifie la valeur de la barre d'erreur dans la direction négative. |
| [getYMinus()](#getYMinus--) | Spécifie la valeur de la barre d'erreur dans la direction négative. |
| [getXPlus()](#getXPlus--) | Spécifie la valeur de la barre d'erreur dans la direction positive. |
| [getYPlus()](#getYPlus--) | Spécifie la valeur de la barre d'erreur dans la direction positive. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Spécifie la valeur de la barre d'erreur dans la direction négative. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsXFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Spécifie la valeur de la barre d'erreur dans la direction négative. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsYFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Spécifie la valeur de la barre d'erreur dans la direction positive. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsXFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Spécifie la valeur de la barre d'erreur dans la direction positive. Disponible si le type de valeur des barres d'erreur est Custom et que ErrorBarsYFormat est autorisé. Dans tout autre cas, cette propriété renvoie null. Lecture seule [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Renvoie:**  
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)