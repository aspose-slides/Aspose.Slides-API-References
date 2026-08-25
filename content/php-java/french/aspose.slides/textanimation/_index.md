---
title: TextAnimation
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/textanimation/
---
## TextAnimation classe

 Représente l'animation de texte.
 
### TextAnimation {#TextAnimation}

| Nom | Description |
| --- | --- |
| TextAnimation() |  |

 **Renvoie:**  
TextAnimation


---


### addEffect {#addEffect}

| Nom | Description |
| --- | --- |
| addEffect (int, int, int) | Ajoute un nouvel effet à la fin de la séquence actuelle jusqu'à la fin du groupe d'animations de texte. Valide uniquement si le nombre de paragraphes de texte est égal ou supérieur au nombre d'effets de ce groupe ! |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| effectType | int | Type d'un effet d'animation EffectType |
| subtype | int | Sous-types de l'effet d'animation EffectSubtype |
| triggerType | int | Type de déclenchement de l'effet EffectTriggerType |

 **Renvoie:**  
[Effect](../effect)


---


### getBuildType {#getBuildType}

| Nom | Description |
| --- | --- |
| getBuildType () | Liste du type de construction (par ex. Paragraph 1,2,3, All at Once) de l'animation de texte. Lecture/écriture BuildType. |

 **Renvoie:**  
int


---


### getEffectAnimateBackgroundShape {#getEffectAnimateBackgroundShape}

| Nom | Description |
| --- | --- |
| getEffectAnimateBackgroundShape () | Effet de forme liée au groupe ou non (null). Lecture/écriture IEffect. |

 **Renvoie:**  
[Effect](../effect)


---


### setBuildType {#setBuildType}

| Nom | Description |
| --- | --- |
| setBuildType (int) | Liste du type de construction (par ex. Paragraph 1,2,3, All at Once) de l'animation de texte. Lecture/écriture BuildType. |

 **Renvoie:**  
void


---


### setEffectAnimateBackgroundShape {#setEffectAnimateBackgroundShape}

| Nom | Description |
| --- | --- |
| setEffectAnimateBackgroundShape ([Effect](../effect)) | Effet de forme liée au groupe ou non (null). Lecture/écriture IEffect. |

 **Renvoie:**  
void


---