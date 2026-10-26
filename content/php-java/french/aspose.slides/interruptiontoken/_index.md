---
title: InterruptionToken
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/interruptiontoken/
---
## InterruptionToken classe

 Cette classe représente le jeton à utiliser pour signaler aux tâches longues si l’interruption a été demandée.
 
### getNone {#getNone}

| Nom | Description |
| --- | --- |
| getNone () | Représente un jeton d’interruption vide. Les opérations longues ne seront jamais interrompues via InterruptionTokenSource#interrupt lors de l’utilisation de ce jeton. |

 **Retourne :**
InterruptionToken


---


### isInterruptionRequested {#isInterruptionRequested}

| Nom | Description |
| --- | --- |
| isInterruptionRequested () | Renvoie true si l’interruption a été demandée. |

 **Retourne :**
boolean


---


### throwIfInterruptionRequested {#throwIfInterruptionRequested}

| Nom | Description |
| --- | --- |
| throwIfInterruptionRequested () | Lance une exception si l’interruption a été demandée. |

 **Retourne :**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
 | OperationCanceledException | Lancée lorsque l’interruption a été demandée. |


---