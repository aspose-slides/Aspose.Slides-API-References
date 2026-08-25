---
title: PresentationAnimationsGenerator
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/presentationanimationsgenerator/
---
## classe PresentationAnimationsGenerator

 Représente un générateur des animations dans la Presentation.
 
### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator([Presentation](../presentation)) | Crée une nouvelle instance de PresentationAnimationsGenerator. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | La taille du cadre sera définie conformément à Presentation#getSlideSize |

 **Valeur de retour :**
PresentationAnimationsGenerator


---

### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension) | Crée une nouvelle instance de PresentationAnimationsGenerator. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension | La taille du cadre. |

 **Valeur de retour :**
PresentationAnimationsGenerator


---

### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| Name | Description |
| --- | --- |
| PresentationAnimationsGenerator(Dimension2D) | Crée une nouvelle instance de PresentationAnimationsGenerator. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| frameSize | Dimension2D | La taille du cadre. |

 **Valeur de retour :**
PresentationAnimationsGenerator


---

### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Libère l'instance de PresentationAnimationsGenerator. |

 **Valeur de retour :**
void


---

### getDefaultDelay {#getDefaultDelay}

| Name | Description |
| --- | --- |
| getDefaultDelay () | Obtient ou définit le délai par défaut [ms]. |

 **Valeur de retour :**
int


---

### getExportedSlides {#getExportedSlides}

| Name | Description |
| --- | --- |
| getExportedSlides () | Obtient le nombre de diapositives exportées. |

 **Valeur de retour :**
int


---

### getFrameSize {#getFrameSize}

| Name | Description |
| --- | --- |
| getFrameSize () | Obtient la taille du cadre. |

 **Valeur de retour :**
Dimension


---

### getIncludeHiddenSlides {#getIncludeHiddenSlides}

| Name | Description |
| --- | --- |
| getIncludeHiddenSlides () | Obtient ou définit si les diapositives masquées doivent être incluses. |

 **Valeur de retour :**
boolean


---

### run {#run}

| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>) | Exécute la génération des événements d'animation pour chaque diapositive. |

 **Valeur de retour :**
void


---

### run {#run}

| Name | Description |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>, int, [PresentationPlayer.FrameTick](../presentationplayer.frametick)) | Exécute la génération des événements d'animation pour chaque diapositive. |

 **Valeur de retour :**
void


---

### setDefaultDelay {#setDefaultDelay}

| Name | Description |
| --- | --- |
| setDefaultDelay (int) | Obtient ou définit le délai par défaut [ms]. |

 **Valeur de retour :**
void


---

### setIncludeHiddenSlides {#setIncludeHiddenSlides}

| Name | Description |
| --- | --- |
| setIncludeHiddenSlides (boolean) | Obtient ou définit si les diapositives masquées doivent être incluses. |

 **Valeur de retour :**
void


---

### setNewAnimation {#setNewAnimation}

| Name | Description |
| --- | --- |
| setNewAnimation ([PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation)) | Définit un nouvel événement d'animation. |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| anim | [PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation) | Événement d'animation. |

 **Valeur de retour :**
void


---