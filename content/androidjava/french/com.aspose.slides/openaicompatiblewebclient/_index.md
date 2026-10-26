---
title: OpenAICompatibleWebClient
second_title: Référence API Java d'Aspose.Slides pour Android
description: Une implémentation intégrée qui se connecte à un fournisseur LLM compatible OpenAI à une URL de base spécifiée.
type: docs
url: /fr/com.aspose.slides/openaicompatiblewebclient/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) intégrée qui se connecte à un fournisseur LLM compatible OpenAI à une URL de base spécifiée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Creates an instance of the OpenAI-compatible web client. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Creates an instance of the OpenAI-compatible web client that uses an externally managed  HttpURLConnection . |

## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using an externally managed HttpURLConnection instance and returns response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
| [dispose()](#dispose--) | Releases resources used by this instance. |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Crée une instance du client Web compatible OpenAI.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Nom du modèle pris en charge par le fournisseur LLM. |
| apiKey | java.lang.String | Clé API (jeton). |
| baseUrl | java.lang.String | URL de base du LLM compatible OpenAI. |
```
OpenAICompatibleWebClient aiClient =
         new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1");
 try {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (aiClient != null) aiClient.dispose();
 }
``` |

### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)
```

Crée une instance du client Web compatible OpenAI qui utilise un HttpURLConnection géré externement. Le HttpURLConnection fourni n'est pas libéré par cette instance et reste la propriété de l'appelant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Nom du modèle pris en charge par le fournisseur LLM. |
| apiKey | java.lang.String | Clé API (jeton). |
| baseUrl | java.lang.String | URL de base du LLM compatible OpenAI. |
| httpClient | java.net.HttpURLConnection | Une instance de HttpURLConnection gérée externement. |
```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     OpenAICompatibleWebClient aiClient =
             new OpenAICompatibleWebClient("model-name", apiKey, "https://api.llm-provider.com/v1", httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     Presentation presentation = new Presentation("Presentation.pptx");
     try {
         aiAgent.translate(presentation, "spanish");
         presentation.save("translated.pptx", SaveFormat.Pptx);
     } finally {
         if (presentation != null) presentation.dispose();
     }
 } finally {
     if (httpClient != null) httpClient.disconnect();
 }
``` |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envoie une instruction de chat au modèle IA en utilisant une instance de HttpURLConnection gérée externement et renvoie le message de réponse à l'instruction donnée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle IA. |

**Retour:**
java.lang.String - Le message généré par le modèle IA en réponse à l'instruction donnée.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels IA classiques, les conversations conservent l'intégralité du contexte.

**Retour:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées par cette instance.