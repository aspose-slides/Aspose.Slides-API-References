---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Représente un hyperlien.
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
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Représente un hyperlien défini pour cette portion sans tenir compte du contenu réel de la portion. |
| [getTargetSlide()](#getTargetSlide--) | Si le HyperlinkEx cible une diapositive spécifique, renvoie cette diapositive. |
| [getTargetFrame()](#getTargetFrame--) | Renvoie le cadre au sein du frameset HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Renvoie le cadre au sein du frameset HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [getTooltip()](#getTooltip--) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur en tant qu'association avec l'hyperlien parent. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur en tant qu'association avec l'hyperlien parent. |
| [getHistory()](#getHistory--) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'elle est invoquée. |
| [setHistory(boolean value)](#setHistory-boolean-) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'elle est invoquée. |
| [getHighlightClick()](#getHighlightClick--) | Détermine si l'hyperlien doit être mis en surbrillance au clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Détermine si l'hyperlien doit être mis en surbrillance au clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| [getSound()](#getSound--) | Représente le son en cours de lecture de l'hyperlien. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Représente le son en cours de lecture de l'hyperlien. |
| [getColorSource()](#getColorSource--) | Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la portion. |
| [setColorSource(int value)](#setColorSource-int-) | Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la portion. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Détermine si les deux instances Hyperlink sont égales. |

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

Représente un hyperlien défini pour cette portion sans tenir compte du contenu réel de la portion.

PowerPoint se comporte de façon spécifique pour les liens et le texte correspondant dans une portion. Il permet de créer du texte pour l'hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous voyez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien.

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

Renvoie le cadre au sein du frameset HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Renvoie le cadre au sein du frameset HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur en tant qu'association avec l'hyperlien parent. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur en tant qu'association avec l'hyperlien parent. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'elle est invoquée. Lecture/écriture boolean.

**Renvoie :**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'elle est invoquée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Détermine si l'hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Renvoie :**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Détermine si l'hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean.

**Renvoie :**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Représente le son en cours de lecture de l'hyperlien. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Represents the playing sound of the hyperlink. Read/write [IAudio](../../com.aspose.slides/iaudio).

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
>          // Extraire le son de l'hyperlien dans un tableau d'octets
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)


Détermine si les deux instances Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | L'Hyperlink à comparer avec l'Hyperlink actuel. |

**Renvoie :**
boolean - **true** si l'Hyperlink spécifié est égal à l'Hyperlink actuel ; sinon, **false**.