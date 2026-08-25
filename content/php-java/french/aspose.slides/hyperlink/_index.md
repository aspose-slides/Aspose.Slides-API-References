---
title: Hyperlink
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/hyperlink/
---
## Hyperlink classe

 Représente un hyperlien.
 
### Hyperlink {#Hyperlink}

| Nom | Description |
| --- | --- |
| Hyperlink(String) | Crée une instance d'un hyperlien. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| url | String | URL de l'hyperlien. |

 **Renvoie:**
Hyperlink


---


### Hyperlink {#Hyperlink}

| Nom | Description |
| --- | --- |
| Hyperlink([Slide](../slide)) | Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique. Note : l'hyperlien créé doit être assigné à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| slide | [Slide](../slide) | Diapositive cible. |

 **Renvoie:**
Hyperlink


---


### Hyperlink {#Hyperlink}

| Nom | Description |
| --- | --- |
| Hyperlink([Hyperlink](../hyperlink), String, String, boolean, boolean, boolean) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en surchargeant les propriétés secondaires. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| source | [Hyperlink](../hyperlink) | Hyperlien source |
| targetFrame | String | Cadre cible |
| tooltip | String | Texte d'infobulle |
| history | boolean | Détermine si la cible du hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. |
| stopSoundsOnClick | boolean | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. |
| highlightClick | boolean | Détermine si l'hyperlien doit être mis en évidence lors du clic. |

 **Renvoie:**
Hyperlink


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals (Object) | Détermine si les deux instances de Hyperlink sont égales. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| obj | Object | L'Hyperlink à comparer avec l'Hyperlink actuel. |

 **Renvoie:**
boolean


---


### equals {#equals}

| Nom | Description |
| --- | --- |
| equals ([Hyperlink](../hyperlink)) | Détermine si les deux instances de Hyperlink sont égales. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| hlink | [Hyperlink](../hyperlink) | L'Hyperlink à comparer avec l'Hyperlink actuel. |

 **Renvoie:**
boolean


---


### getActionType {#getActionType}

| Nom | Description |
| --- | --- |
| getActionType () | Renvoie le type de l'action de l'Hyperlink. Lecture seule HyperlinkActionType. |

 **Renvoie:**
int


---


### getColorSource {#getColorSource}

| Nom | Description |
| --- | --- |
| getColorSource () | Représente la source de la couleur du hyperlien - soit les styles, soit le format de portion. Lecture/écriture HyperlinkColorSource. |

 **Renvoie:**
int


---


### getEndShow {#getEndShow}

| Nom | Description |
| --- | --- |
| getEndShow () | Renvoie un hyperlien qui termine le diaporama. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getExternalUrl {#getExternalUrl}

| Nom | Description |
| --- | --- |
| getExternalUrl () | Spécifie l'URL externe. Lecture seule String. |

 **Renvoie:**
String


---


### getExternalUrlOriginal {#getExternalUrlOriginal}

| Nom | Description |
| --- | --- |
| getExternalUrlOriginal () | Représente un hyperlien qui est défini pour cette portion sans tenir compte du contenu réel de la portion. PowerPoint se comporte spécifiquement pour les liens et le texte correspondant dans une portion. Il permet de créer du texte pour l'hyperlien sous la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien. |

 **Renvoie:**
String


---


### getFirstSlide {#getFirstSlide}

| Nom | Description |
| --- | --- |
| getFirstSlide () | Renvoie un hyperlien vers la première diapositive de la présentation. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getHighlightClick {#getHighlightClick}

| Nom | Description |
| --- | --- |
| getHighlightClick () | Détermine si l'hyperlien doit être mis en évidence lors du clic. Lecture/écriture boolean. |

 **Renvoie:**
boolean


---


### getHistory {#getHistory}

| Nom | Description |
| --- | --- |
| getHistory () | Détermine si la cible du hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean. |

 **Renvoie:**
boolean


---


### getLastSlide {#getLastSlide}

| Nom | Description |
| --- | --- |
| getLastSlide () | Renvoie un hyperlien vers la dernière diapositive de la présentation. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getLastVievedSlide {#getLastVievedSlide}

| Nom | Description |
| --- | --- |
| getLastVievedSlide () | Renvoie un hyperlien vers la dernière diapositive consultée. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getMedia {#getMedia}

| Nom | Description |
| --- | --- |
| getMedia () | Renvoie un hyperlien spécial "play mediafile". Utilisé dans AudioFrame et VideoFrame. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getNextSlide {#getNextSlide}

| Nom | Description |
| --- | --- |
| getNextSlide () | Renvoie un hyperlien vers la diapositive suivante. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getNoAction {#getNoAction}

| Nom | Description |
| --- | --- |
| getNoAction () | Renvoie un hyperlien spécial "do nothing". Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getPreviousSlide {#getPreviousSlide}

| Nom | Description |
| --- | --- |
| getPreviousSlide () | Renvoie un hyperlien vers la diapositive précédente. Lecture seule Hyperlink. |

 **Renvoie:**
Hyperlink


---


### getSound {#getSound}

| Nom | Description |
| --- | --- |
| getSound () | Représente le son en lecture de l'hyperlien. Lecture/écriture IAudio. |

 **Renvoie:**
[Audio](../audio)


---


### getStopSoundOnClick {#getStopSoundOnClick}

| Nom | Description |
| --- | --- |
| getStopSoundOnClick () | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean. |

 **Renvoie:**
boolean


---


### getTargetFrame {#getTargetFrame}

| Nom | Description |
| --- | --- |
| getTargetFrame () | Renvoie le cadre au sein du frameset HTML parent pour la cible du hyperlien parent lorsqu'il existe. Lecture/écriture String. |

 **Renvoie:**
String


---


### getTargetSlide {#getTargetSlide}

| Nom | Description |
| --- | --- |
| getTargetSlide () | Si l'Hyperlink cible une diapositive spécifique, renvoie cette diapositive. Lecture seule ISlide. |

 **Renvoie:**
[Slide](../slide)


---


### getTooltip {#getTooltip}

| Nom | Description |
| --- | --- |
| getTooltip () | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. Lecture/écriture String. |

 **Renvoie:**
String


---


### getVersion {#getVersion}

| Nom | Description |
| --- | --- |
| getVersion () |  |

 **Renvoie:**
long


---


### hashCode {#hashCode}

| Nom | Description |
| --- | --- |
| hashCode () | Servit de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |

 **Renvoie:**
int


---


### op_Equality {#op_Equality}

| Nom | Description |
| --- | --- |
| op_Equality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Teste deux hyperliens pour l'égalité. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | Premier hyperlien à tester. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlien à tester. |

 **Renvoie:**
boolean


---


### op_Inequality {#op_Inequality}

| Nom | Description |
| --- | --- |
| op_Inequality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | Teste deux hyperliens pour la différence. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | Premier hyperlien à tester. |
| hlink2 | [Hyperlink](../hyperlink) | Second hyperlien à tester. |

 **Renvoie:**
boolean


---


### setColorSource {#setColorSource}

| Nom | Description |
| --- | --- |
| setColorSource (int) | Représente la source de la couleur du hyperlien - soit les styles, soit le format de portion. Lecture/écriture HyperlinkColorSource. |

 **Renvoie:**
void


---


### setHighlightClick {#setHighlightClick}

| Nom | Description |
| --- | --- |
| setHighlightClick (boolean) | Détermine si l'hyperlien doit être mis en évidence lors du clic. Lecture/écriture boolean. |

 **Renvoie:**
void


---


### setHistory {#setHistory}

| Nom | Description |
| --- | --- |
| setHistory (boolean) | Détermine si la cible du hyperlien parent doit être ajoutée à une liste d'hyperliens consultés lorsqu'il est invoqué. Lecture/écriture boolean. |

 **Renvoie:**
void


---


### setSound {#setSound}

| Nom | Description |
| --- | --- |
| setSound ([Audio](../audio)) | Représente le son en lecture de l'hyperlien. Lecture/écriture IAudio. |

 **Renvoie:**
void


---


### setStopSoundOnClick {#setStopSoundOnClick}

| Nom | Description |
| --- | --- |
| setStopSoundOnClick (boolean) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien. Lecture/écriture boolean. |

 **Renvoie:**
void


---


### setTargetFrame {#setTargetFrame}

| Nom | Description |
| --- | --- |
| setTargetFrame (String) | Retourne le cadre au sein du frameset HTML parent pour la cible du hyperlien parent lorsqu'il existe. Lecture/écriture String. |

 **Renvoie:**
void


---


### setTooltip {#setTooltip}

| Nom | Description |
| --- | --- |
| setTooltip (String) | Retourne la chaîne qui peut être affichée dans une interface utilisateur associée au hyperlien parent. Lecture/écriture String. |

 **Renvoie:**
void


---