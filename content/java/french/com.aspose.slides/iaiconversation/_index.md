---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Represents a conversation instance.
type: docs
url: /fr/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Représente une instance de conversation. Contrairement aux appels d'IA classiques, les conversations conservent tout le contexte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Envoie le message de requête de conversation incluant tout le contexte et renvoie la réponse. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Envoie le message de requête de conversation incluant tout le contexte et renvoie la réponse.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle d'IA. |

**Renvoie :**
java.lang.String - Le message généré par le modèle d'IA en réponse à l'instruction donnée dans le contexte de la conversation.