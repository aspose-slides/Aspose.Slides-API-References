---
title: Trendline
second_title: Référence de l'API Aspose.Slides pour Java
description: Classe représentant la ligne de tendance d'une série de graphique
type: docs
url: /fr/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

La classe représente la ligne de tendance d’une série de graphique
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtient ou définit le nom de la ligne de tendance. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtient ou définit le nom de la ligne de tendance. |
| [getTrendlineType()](#getTrendlineType--) | Obtient ou définit le type de ligne de tendance. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtient ou définit le type de ligne de tendance. |
| [getFormat()](#getFormat--) | Représente le format de la ligne de tendance. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente le format de la ligne de tendance. |
| [getBackward()](#getBackward--) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend avant les données de la série étudiée. |
| [setBackward(double value)](#setBackward-double-) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend avant les données de la série étudiée. |
| [getForward()](#getForward--) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend après les données de la série étudiée. |
| [setForward(double value)](#setForward-double-) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend après les données de la série étudiée. |
| [getIntercept()](#getIntercept--) | Spécifie la valeur où la ligne de tendance doit croiser l’axe y. |
| [setIntercept(double value)](#setIntercept-double-) | Spécifie la valeur où la ligne de tendance doit croiser l’axe y. |
| [getDisplayEquation()](#getDisplayEquation--) | Indique que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Indique que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). |
| [getOrder()](#getOrder--) | Spécifie l’ordre de la ligne de tendance polynomiale. |
| [setOrder(byte value)](#setOrder-byte-) | Spécifie l’ordre de la ligne de tendance polynomiale. |
| [getPeriod()](#getPeriod--) | Spécifie la période de la ligne de tendance pour une moyenne mobile. |
| [setPeriod(byte value)](#setPeriod-byte-) | Spécifie la période de la ligne de tendance pour une moyenne mobile. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Indique que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Indique que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Représente l’entrée de légende associée à cette ligne de tendance Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Initialise TextFrameForOverriding avec le texte du paramètre "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Peut contenir un texte riche formaté. |
| [getTextFormat()](#getTextFormat--) | Renvoie le format du texte. |
| [getChart()](#getChart--) | Renvoie le graphique parent. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d’un FillFormat. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d’un FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```


Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```


Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```


Obtient ou définit le type de ligne de tendance. Lecture/écriture [TrendlineType](../../com.aspose.slides/trendlinetype).

**Renvoie :**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```


Obtient ou définit le type de ligne de tendance. Lecture/écriture [TrendlineType](../../com.aspose.slides/trendlinetype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Représente le format de la ligne de tendance. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Représente le format de la ligne de tendance. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```


Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend avant les données de la série étudiée. Sur les graphiques en nuage de points et les autres graphiques, la valeur doit être non négative. Lecture/écriture double.

**Renvoie :**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```


Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend avant les données de la série étudiée. Sur les graphiques en nuage de points et les autres graphiques, la valeur doit être non négative. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```


Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend après les données de la série étudiée. Sur les graphiques en nuage de points et les autres graphiques, la valeur doit être non négative. Lecture/écriture double.

**Renvoie :**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```


Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance s’étend après les données de la série étudiée. Sur les graphiques en nuage de points et les autres graphiques, la valeur doit être non négative. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```


Spécifie la valeur où la ligne de tendance doit croiser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Lecture/écriture double.

**Renvoie :**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```


Spécifie la valeur où la ligne de tendance doit croiser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linear ou poly. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```


Indique que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). Lecture/écriture boolean.

**Renvoie :**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```


Indique que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```


Spécifie l’ordre de la ligne de tendance polynomiale. Ignoré pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte.

**Renvoie :**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```


Spécifie l’ordre de la ligne de tendance polynomiale. Ignoré pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```


Spécifie la période de la ligne de tendance pour une moyenne mobile. Ignoré pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte.

**Renvoie :**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```


Spécifie la période de la ligne de tendance pour une moyenne mobile. Ignoré pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```


Indique que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean.

**Renvoie :**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```


Indique que la valeur R-squared de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Représente l’entrée de légende liée à cette ligne de tendance Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Renvoie :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


Initialise TextFrameForOverriding avec le texte du paramètre "text". Si TextFrameForOverriding est déjà initialisé, le texte est simplement modifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte pour un nouveau TextFrameForOverriding. |

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


Peut contenir un texte riche formaté. Si cette propriété n’est pas nulle, ce texte formaté remplace le texte auto-généré de l’étiquette de données. Le texte auto-généré d’une étiquette de données désigne le texte géré par les propriétés ShowSeriesName, ShowValue, … et formaté avec la propriété TextFormatManager.TextFormat. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Renvoie le format du texte. Lecture seule [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Renvoie :**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Renvoie le graphique parent. Lecture seule [IChart](../../com.aspose.slides/ichart).

**Renvoie :**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Renvoie la diapositive parent d’un FillFormat. Lecture seule [BaseSlide](../../com.aspose.slides/baseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie la présentation parent d’un FillFormat. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)