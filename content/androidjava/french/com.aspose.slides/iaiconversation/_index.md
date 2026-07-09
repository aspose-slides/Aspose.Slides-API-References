---
title: IAIConversation
second_title: Aspose.Slides pour Android via la Référence API Java
description: Représente une instance de conversation.
type: docs
url: /fr/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Représente une instance de conversation. Contrairement aux appels d'IA réguliers, les conversations conservent le contexte complet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Envoie un message de requête de conversation incluant le contexte complet et renvoie la réponse. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Envoie un message de requête de conversation incluant le contexte complet et renvoie la réponse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle d'IA. |

**Retour :**
java.lang.String - Le message généré par le modèle d'IA en réponse à l'instruction donnée dans le contexte de la conversation.