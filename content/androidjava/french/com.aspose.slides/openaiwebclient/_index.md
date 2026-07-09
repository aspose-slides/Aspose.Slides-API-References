---
title: OpenAIWebClient
second_title: Référence de l’API Java d’Aspose.Slides pour Android
description: Client Web OpenAI léger intégré
type: docs
url: /fr/com.aspose.slides/openaiwebclient/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable  
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Client Web OpenAI léger intégré

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crée une instance du client Web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client Web OpenAI. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envoie une instruction de chat au modèle IA en utilisant une instance gérée à l'extérieur et renvoie le message de réponse à l’instruction donnée. |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [close()](#close--) | Libère les ressources utilisées par cette instance. |

### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Crée une instance du client Web OpenAI.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Modèle de langue OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clé API OpenAI |
| organizationId | java.lang.String | Identifiant d’organisation (facultatif) |

### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Crée une instance du client Web OpenAI.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Modèle de langue OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clé API OpenAI |
| organizationId | java.lang.String | Identifiant d’organisation (facultatif) |
| httpClient | java.net.HttpURLConnection | Une instance HttpURLConnection gérée à l’extérieur. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envoie une instruction de chat au modèle IA en utilisant une instance gérée à l’extérieur et renvoie le message de réponse à l’instruction donnée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L’instruction ou le message à traiter par le modèle IA |

**Renvoie:**
java.lang.String - Le message généré par le modèle IA en réponse à l’instruction donnée.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels IA classiques, les conversations conservent tout le contexte.

**Renvoie:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).

### close() {#close--}
```
public final void close()
```

Libère les ressources utilisées par cette instance.