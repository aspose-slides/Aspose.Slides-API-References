---
title: Hyperlink
second_title: Référence de l'API Aspose.Slides pour Java
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
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en écrasant les propriétés secondaires. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Renvoie un hyperlien spécial « ne rien faire ». |
| [getMedia()](#getMedia--) | Renvoie un hyperlien spécial « lecture du fichier média ». |
| [getNextSlide()](#getNextSlide--) | Renvoie un hyperlien vers la diapositive suivante. |
| [getPreviousSlide()](#getPreviousSlide--) | Renvoie un hyperlien vers la diapositive précédente. |
| [getFirstSlide()](#getFirstSlide--) | Renvoie un hyperlien vers la première diapositive de la présentation. |
| [getLastSlide()](#getLastSlide--) | Renvoie un hyperlien vers la dernière diapositive de la présentation. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Renvoie un hyperlien vers la dernière diapositive consultée. |
| [getEndShow()](#getEndShow--) | Renvoie un hyperlien qui termine le diaporama. |
| [getActionType()](#getActionType--) | Renvoie le type d'action de l'hyperlien. |
| [getExternalUrl()](#getExternalUrl--) | Spécifie l'URL externe. |
| [getTargetSlide()](#getTargetSlide--) | Si l'hyperlien cible une diapositive spécifique, renvoie cette diapositive. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Représente un hyperlien défini pour cette partie sans tenir compte du contenu réel de la partie. |
| [getTargetFrame()](#getTargetFrame--) | Renvoie le cadre dans l'ensemble de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Renvoie le cadre dans l'ensemble de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. |
| [getTooltip()](#getTooltip--) | Renvoie la chaîne pouvant être affichée dans une interface utilisateur associée à l'hyperlien parent. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Renvoie la chaîne pouvant être affichée dans une interface utilisateur associée à l'hyperlien parent. |
| [getHistory()](#getHistory--) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. |
| [setHistory(boolean value)](#setHistory-boolean-) | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. |
| [getHighlightClick()](#getHighlightClick--) | Détermine si l'hyperlien doit être mis en évidence au clic. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Détermine si l'hyperlien doit être mis en évidence au clic. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| [getSound()](#getSound--) | Représente le son en cours de lecture de l'hyperlien. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Représente le son en cours de lecture de l'hyperlien. |
| [getColorSource()](#getColorSource--) | Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la partie. |
| [setColorSource(int value)](#setColorSource-int-) | Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la partie. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si les deux instances d'Hyperlink sont égales. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Détermine si les deux instances d'Hyperlink sont égales. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste deux hyperliens pour l'égalité. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Teste deux hyperliens pour l'inégalité. |
| [hashCode()](#hashCode--) | Fonctionne comme fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
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

Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Remarque : l'hyperlien créé doit être affecté à un objet de la même présentation, sinon le lien sera enregistré comme NoAction.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive cible. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en écrasant les propriétés secondaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlien source |
| targetFrame | java.lang.String | Cadre cible |
| tooltip | java.lang.String | Texte de l'infobulle |
| history | boolean | Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. |
| stopSoundsOnClick | boolean | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| highlightClick | boolean | Détermine si l'hyperlien doit être mis en évidence au clic. |

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

Renvoie un hyperlien spécial « ne rien faire ». Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

**Renvoie :**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Renvoie un hyperlien spécial « lecture du fichier média ». Utilisé dans AudioFrame et VideoFrame. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

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

Renvoie un hyperlien vers la dernière diapositive consultée. Lecture seule [Hyperlink](../../com.aspose.slides/hyperlink).

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

Représente un hyperlien défini pour cette partie sans tenir compte du contenu réel de la partie.

--------------------

PowerPoint se comporte de manière spécifique pour les liens et le texte correspondant dans une portion. Il permet de créer le texte de l'hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien.

**Renvoie :**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Renvoie le cadre dans l'ensemble de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Renvoie le cadre dans l'ensemble de cadres HTML parent pour la cible de l'hyperlien parent lorsqu'il existe. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Renvoie la chaîne pouvant être affichée dans une interface utilisateur associée à l'hyperlien parent. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Renvoie la chaîne pouvant être affichée dans une interface utilisateur associée à l'hyperlien parent. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean.

**Renvoie :**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Détermine si la cible de l'hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Détermine si l'hyperlien doit être mis en évidence au clic. Lecture/écriture boolean.

**Renvoie :**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Détermine si l'hyperlien doit être mis en évidence au clic. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean.

**Renvoie :**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean.

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
>      // Récupérer le premier hyperlien de la forme
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
```

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Représente le son en cours de lecture de l'hyperlien. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Récupérer le premier hyperlien de la forme
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
```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la partie. Lecture/écriture [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Renvoie :**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la partie. Lecture/écriture [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si les deux instances d'Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'hyperlien à comparer avec l'hyperlien actuel. |

**Renvoie :**
boolean - **true** si l'hyperlien spécifié est égal à l'hyperlien actuel ; sinon, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Détermine si les deux instances d'Hyperlink sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | L'hyperlien à comparer avec l'hyperlien actuel. |

**Renvoie :**
boolean - **true** si l'hyperlien spécifié est égal à l'hyperlien actuel ; sinon, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Teste deux hyperliens pour l'égalité.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Premier hyperlien à tester. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Deuxième hyperlien à tester. |

**Renvoie :**
boolean - **true** si les hyperliens sont égaux.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Teste deux hyperliens pour l'inégalité.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Premier hyperlien à tester. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Deuxième hyperlien à tester. |

**Renvoie :**
boolean - **false** si les hyperliens sont égaux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fonctionne comme fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.

**Renvoie :**
int - Code de hachage pour une URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject