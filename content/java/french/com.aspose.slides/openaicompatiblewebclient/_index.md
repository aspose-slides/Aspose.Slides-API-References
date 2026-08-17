---
title: OpenAICompatibleWebClient
second_title: Référence de l'API Aspose.Slides pour Java
description: Une implémentation intégrée qui se connecte à un fournisseur LLM compatible OpenAI à une URL de base spécifiée.
type: docs
url: /fr/com.aspose.slides/openaicompatiblewebclient/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class OpenAICompatibleWebClient implements IAIWebClient, System.IDisposable
```

Une implémentation intégrée [IAIWebClient](../../com.aspose.slides/iaiwebclient) qui se connecte à un fournisseur LLM compatible OpenAI à une URL de base spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crée une instance du client web compatible OpenAI. |
| [OpenAICompatibleWebClient(String model, String apiKey, String baseUrl, HttpURLConnection httpClient)](#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client web compatible OpenAI qui utilise un HttpURLConnection géré en externe . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envoie une instruction de chat au modèle d'IA en utilisant une instance HttpURLConnection gérée en externe et renvoie le message de réponse à l'instruction donnée. |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [dispose()](#dispose--) | Libère les ressources utilisées par cette instance. |
### OpenAICompatibleWebClient(String model, String apiKey, String baseUrl) {#OpenAICompatibleWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAICompatibleWebClient(String model, String apiKey, String baseUrl)
```

Crée une instance du client web compatible OpenAI.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Nom du modèle pris en charge par le fournisseur LLM. |
| apiKey | java.lang.String | Clé API (jeton). |
| baseUrl | java.lang.String | URL de base du LLM compatible OpenAI.

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

Crée une instance du client web compatible OpenAI qui utilise un HttpURLConnection géré en externe . Le HttpURLConnection fourni n'est pas libéré par cette instance et reste la propriété de l'appelant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Nom du modèle pris en charge par le fournisseur LLM. |
| apiKey | java.lang.String | Clé API (jeton). |
| baseUrl | java.lang.String | URL de base du LLM compatible OpenAI. |
| httpClient | java.net.HttpURLConnection | Une instance HttpURLConnection gérée en externe.

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

Envoie une instruction de chat au modèle d'IA en utilisant une instance HttpURLConnection gérée en externe et renvoie le message de réponse à l'instruction donnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L'instruction ou le message à traiter par le modèle d'IA. |

**Renvoie :**
java.lang.String - Le message généré par le modèle d'IA en réponse à l'instruction donnée.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels d'IA habituels, les conversations conservent tout le contexte.

**Renvoie :**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### dispose() {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées par cette instance.