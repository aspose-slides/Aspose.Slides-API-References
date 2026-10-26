---
title: IAIWebClient
second_title: Aspose.Slides pour Android via Java API Reference
description: Interface client Web IA.
type: docs
url: /fr/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interface client Web IA. Cette interface permet de substituer différents modèles de langage IA. Les classes qui implémentent cette interface sont censées être utilisées avec SlidesAIAgent.
## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Envoie une instruction de chat au modèle IA en utilisant une instance HttpConnection fournie et renvoie le message de réponse à l'instruction donnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle IA. |

**Retour :**
java.lang.String - Le message généré par le modèle IA en réponse à l'instruction donnée.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels IA classiques, les conversations conservent l'intégralité du contexte.

**Retour :**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une [IAIConversation](../../com.aspose.slides/iaiconversation) instance.