---
title: AutoShape
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/autoshape/
---
## AutoShape classe

  Représente un AutoShape.
 
### addTextFrame {#addTextFrame}

| Name | Description |
| --- | --- |
| addTextFrame (String) | Ajoute un nouveau TextFrame à une forme. Si la forme possède déjà un TextFrame, il modifie simplement son texte. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | Texte par défaut pour un nouveau TextFrame. |

 **Retour:**
[TextFrame](../textframe)


---


### getAutoShapeLock {#getAutoShapeLock}

| Name | Description |
| --- | --- |
| getAutoShapeLock () | Renvoie les verrous de l'autoshape. Lecture seule IAutoShapeLock. |

 **Retour:**
[AutoShapeLock](../autoshapelock)


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock () | Renvoie les verrous de la forme. Lecture seule IAutoShapeLock. |

 **Retour:**
[AutoShapeLock](../autoshapelock)


---


### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame () | Renvoie l'objet TextFrame pour l'AutoShape. Lecture seule ITextFrame. |

 **Retour:**
[TextFrame](../textframe)


---


### getUseBackgroundFill {#getUseBackgroundFill}

| Name | Description |
| --- | --- |
| getUseBackgroundFill () | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen. |

 **Retour:**
boolean


---


### isTextBox {#isTextBox}

| Name | Description |
| --- | --- |
| isTextBox () | Spécifie si la forme est une zone de texte. Si la forme n'est pas spécifiée comme une zone de texte, cela ne signifie pas qu'elle ne peut pas avoir de texte attaché. Une zone de texte n'est qu'une forme spécialisée avec des propriétés spécifiques. |

 **Retour:**
boolean


---


### setUseBackgroundFill {#setUseBackgroundFill}

| Name | Description |
| --- | --- |
| setUseBackgroundFill (boolean) | Détermine si cet autoshape doit être rempli avec le remplissage d'arrière-plan de la diapositive au lieu de celui spécifié par le style ou le format de remplissage. Lecture/écriture booléen. |

 **Retour:**
void


---