---
title: Hyperlink
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un hyperlien.
type: docs
url: /fr/com.aspose.slides/hyperlink/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Représente un hyperlien.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Crée une instance d'un hyperlien. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en surchargeant les propriétés secondaires. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Renvoie un hyperlien spécial "ne rien faire". |
| [getMedia()](#getMedia--) | Renvoie un hyperlien spécial "lecture du fichier média". |
| [getNextSlide()](#getNextSlide--) | Renvoie un hyperlien vers la diapositive suivante. |
| [getPreviousSlide()](#getPreviousSlide--) | Renvoie un hyperlien vers la diapositive précédente. |
| [getFirstSlide()](#getFirstSlide--) | Renvoie un hyperlien vers la première diapositive de la présentation. |
| [getLastSlide()](#getLastSlide--) | Renvoie un hyperlien vers la dernière diapositive de la présentation. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Renvoie un hyperlien vers la dernière diapositive visualisée. |
| [getEndShow()](#getEndShow--) | Renvoie un hyperlien qui termine le diaporama. |
| [getActionType()](#getActionType--) | Renvoie le type d'action de l'hyperlien. |
| [getExternalUrl()](#getExternalUrl--) | Spécifie l'URL externe. |
| [getTargetSlide()](#getTargetSlide--) | Si l'hyperlien cible une diapositive spécifique, renvoie cette diapositive. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion. |
| [getTargetFrame()](#getTargetFrame--) | Renvoie le cadre du jeu de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Renvoie le cadre du jeu de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [getTooltip()](#getTooltip--) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée à l'hyperlien parent. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée à l'hyperlien parent. |
| [getHistory()](#getHistory--) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. |
| [setHistory(boolean value)](#setHistory-boolean-) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. |
| [getHighlightClick()](#getHighlightClick--) | Détermine si l'hyperlien doit être mis en surbrillance au clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Détermine si l'hyperlien doit être mis en surbrillance au clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Détermine si le son doit être arrêté au clic sur l'hyperlien. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Détermine si le son doit être arrêté au clic sur l'hyperlien. |
| [getSound()](#getSound--) | Représente le son en cours de lecture de l'hyperlien. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Représente le son en cours de lecture de l'hyperlien. |
| [getColorSource()](#getColorSource--) | Représente la source de couleur de l'hyperlien – soit les styles, soit le format de la portion. |
| [setColorSource(int value)](#setColorSource-int-) | Représente la source de couleur de l'hyperlien – soit les styles, soit le format de la portion. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si les deux instances d'Hyperlink sont égales. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Détermine si les deux instances d'Hyperlink sont égales. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste deux hyperliens pour l'égalité. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste deux hyperliens pour l'inégalité. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Crée une instance d'un hyperlien.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL de l'hyperlien. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Remarque : l'hyperlien créé doit être assigné à un objet de la même présentation, sinon le lien sera enregistré comme NoAction.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en surchargeant les propriétés secondaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlien source |
| targetFrame | java.lang.String | Cadre cible |
| tooltip | java.lang.String | Texte de l'infobulle |
| history | boolean | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. |
| stopSoundsOnClick | boolean | Détermine si le son doit être arrêté au clic sur l'hyperlien. |
| highlightClick | boolean | Détermine si l'hyperlien doit être mis en surbrillance au clic. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Renvoie un hyperlien spécial "ne rien faire". Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Renvoie un hyperlien spécial "lecture du fichier média". Utilisé dans AudioFrame et VideoFrame. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Renvoie un hyperlien vers la diapositive suivante. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Renvoie un hyperlien vers la diapositive précédente. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Renvoie un hyperlien vers la première diapositive de la présentation. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Renvoie un hyperlien vers la dernière diapositive de la présentation. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Renvoie un hyperlien vers la dernière diapositive visualisée. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Renvoie un hyperlien qui termine le diaporama. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Renvoie le type d'action de l'hyperlien. Lecture seule [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Renvoie :**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Spécifie l'URL externe. Lecture seule String.

**Renvoie :**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Si l'hyperlien cible une diapositive spécifique, renvoie cette diapositive. Lecture seule [ISlide](../../com.aspose.slides/islide).

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion.

--------------------

PowerPoint se comporte de manière spécifique pour les liens et le texte correspondant dans une portion. Il permet de créer du texte pour l'hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien.

**Renvoie :**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Renvoie le cadre du jeu de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Renvoie le cadre du jeu de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée à l'hyperlien parent. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée à l'hyperlien parent. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. Lecture/écriture boolean.

**Renvoie :**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens visualisés lorsqu'il est invoqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Détermine si l'hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Renvoie :**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Détermine si l'hyperlien doit être mis en surbrillance au clic. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Détermine si le son doit être arrêté au clic sur l'hyperlien. Lecture/écriture boolean.

**Renvoie :**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Détermine si le son doit être arrêté au clic sur l'hyperlien. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Représente le son en cours de lecture de l'hyperlien. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

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
public final void setSound(IAudio value)
```


Represents the playing sound of the hyperlink. Read/write [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Obtenir le lien hypertexte de la première forme
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraire le son du lien hypertexte en tableau d'octets
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
public final int getColorSource()
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```
Détermine si les deux instances de Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le Hyperlink à comparer avec le Hyperlink actuel. |

**Retour :**
boolean - **true** si le Hyperlink spécifié est égal au Hyperlink actuel ; sinon, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Détermine si les deux instances de Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Le Hyperlink à comparer avec le Hyperlink actuel. |

**Retour :**
boolean - **true** si le Hyperlink spécifié est égal au Hyperlink actuel ; sinon, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```
Tests two hyperlinks for equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Tests two hyperlinks for inequality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```
Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Returns:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()


Renvoie Parent_Immediate object. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject