---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Represents a hyperlink.
type: docs
url: /fr/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Représente un hyperlien.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getActionType()](#getActionType--) | Renvoie le type de l'action de HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Spécifie l'URL externe. Si cette propriété devient non nulle, alors la propriété TargetSlide devient nulle. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion. |
| [getTargetSlide()](#getTargetSlide--) | Si le HyperlinkEx cible une diapositive spécifique, renvoie cette diapositive. |
| [getTargetFrame()](#getTargetFrame--) | Renvoie le cadre au sein du jeu de cadres HTML parent pour la cible du hyperlien parent lorsqu'il existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Renvoie le cadre au sein du jeu de cadres HTML parent pour la cible du hyperlien parent lorsqu'il existe. |
| [getTooltip()](#getTooltip--) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. |
| [getHistory()](#getHistory--) | Détermine si la cible du hyperlien parent doit être ajoutée à une liste de hyperliens consultés lorsqu'il est invoqué. |
| [setHistory(boolean value)](#setHistory-boolean-) | Détermine si la cible du hyperlien parent doit être ajoutée à une liste de hyperliens consultés lorsqu'il est invoqué. |
| [getHighlightClick()](#getHighlightClick--) | Détermine si le hyperlien doit être mis en surbrillance au clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Détermine si le hyperlien doit être mis en surbrillance au clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Détermine si le son doit être arrêté lors du clic sur le hyperlien. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Détermine si le son doit être arrêté lors du clic sur le hyperlien. |
| [getSound()](#getSound--) | Représente le son en cours de lecture du hyperlien. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Représente le son en cours de lecture du hyperlien. |
| [getColorSource()](#getColorSource--) | Représente la source de la couleur du hyperlien – soit les styles, soit le format de portion. |
| [setColorSource(int value)](#setColorSource-int-) | Représente la source de la couleur du hyperlien – soit les styles, soit le format de portion. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Détermine si les deux instances de Hyperlink sont égales. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Renvoie le type de l'action de HyperLinkEx. Lecture seule [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Renvoie :**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Spécifie l'URL externe. Si cette propriété devient non nulle, alors la propriété TargetSlide devient nulle. Lecture seule String.

**Renvoie :**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion.

--------------------

PowerPoint se comporte de manière spécifique pour les liens et leur texte correspondant dans une portion. Il permet de créer du texte pour le hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale du hyperlien.

**Renvoie :**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Si le HyperlinkEx cible une diapositive spécifique, renvoie cette diapositive. Si la propriété devient non nulle, alors la propriété ExternalUrl devient nulle. Lecture seule [ISlide](../../com.aspose.slides/islide).

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Renvoie le cadre au sein du jeu de cadres HTML parent pour la cible du hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Renvoie le cadre au sein du jeu de cadres HTML parent pour la cible du hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Détermine si la cible du hyperlien parent doit être ajoutée à une liste de hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Détermine si la cible du hyperlien parent doit être ajoutée à une liste de hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Détermine si le hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Renvoie :**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Détermine si le hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Détermine si le son doit être arrêté lors du clic sur le hyperlien. Lecture/écriture boolean.

**Renvoie :**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Détermine si le son doit être arrêté lors du clic sur le hyperlien. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Représente le son en cours de lecture du hyperlien. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenir le premier hyperlien de forme
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraire le son du hyperlien sous forme de tableau d'octets
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Représente le son en cours de lecture du hyperlien. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenir le premier hyperlien de forme
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraire le son du hyperlien sous forme de tableau d'octets
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Représente la source de la couleur du hyperlien – soit les styles, soit le format de portion. Lecture/écriture [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Renvoie :**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Représente la source de la couleur du hyperlien – soit les styles, soit le format de portion. Lecture/écriture [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Détermine si les deux instances de Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Le Hyperlink à comparer avec le Hyperlink actuel. |

**Renvoie :**
boolean - **true** si le Hyperlink spécifié est égal au Hyperlink actuel ; sinon, **false**.