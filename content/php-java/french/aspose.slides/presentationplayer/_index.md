---
title: PresentationPlayer
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/presentationplayer/
---
## classe PresentationPlayer

 Représente le lecteur d'animations associé à la Presentation. 
 
### PresentationPlayer {#PresentationPlayer}

| Name | Description |
| --- | --- |
| PresentationPlayer([PresentationAnimationsGenerator](../presentationanimationsgenerator), double) | Crée une nouvelle instance de PresentationPlayer. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| generator | [PresentationAnimationsGenerator](../presentationanimationsgenerator) | Générateur d'animations de Presentation |
| fps | double | Images par seconde (FPS) |

 **Renvoie:**
PresentationPlayer


---


### dispose {#dispose}

| Name | Description |
| --- | --- |
| dispose () | Libère l'instance de PresentationPlayer. |

 **Renvoie:**
void


---


### getFrameIndex {#getFrameIndex}

| Name | Description |
| --- | --- |
| getFrameIndex () | Obtient l'index de la trame. |

 **Renvoie:**
int


---


### setFrameTick {#setFrameTick}

| Name | Description |
| --- | --- |
| setFrameTick ([PresentationPlayer.FrameTick](../presentationplayer.frametick)) | Définit un nouvel événement de tick de trame. Se produit lorsque chaque trame de l'animation créée par PresentationAnimationsGenerator est générée par le lecteur. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| event | [PresentationPlayer.FrameTick](../presentationplayer.frametick) | Événement de tick de trame. |

 **Renvoie:**
void


---