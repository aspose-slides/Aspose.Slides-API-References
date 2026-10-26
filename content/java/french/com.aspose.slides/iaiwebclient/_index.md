---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI Web client interface.
type: docs
url: /fr/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interface client Web IA. Cette interface permet de substituer différents modèles de langage IA. Les classes qui implémentent cette interface sont destinées à être utilisées avec SlidesAIAgent.

## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envoie une instruction de chat au modèle d'IA en utilisant une instance HttpConnection fournie et renvoie le message de réponse à l'instruction donnée. |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Envoie une instruction de chat au modèle d'IA en utilisant une instance HttpConnection fournie et renvoie le message de réponse à l'instruction donnée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle d'IA. |

**Renvoie:**
java.lang.String - Le message généré par le modèle d'IA en réponse à l'instruction donnée.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels d'IA classiques, les conversations conservent tout le contexte.

**Renvoie:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).