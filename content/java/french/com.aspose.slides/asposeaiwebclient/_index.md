---
title: AsposeAIWebClient
second_title: Référence de l'API Aspose.Slides pour Java
description: Une implémentation intégrée qui se connecte au propre LLM d'Aspose.
type: docs
url: /fr/com.aspose.slides/asposeaiwebclient/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) intégrée qui se connecte au propre LLM d’Aspose. C’est le client par défaut utilisé par le constructeur sans paramètres  SlidesAIAgent() .

## Constructeurs

| Constructor | Description |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crée une instance du client Web Aspose AI qui se connecte au point de terminaison par défaut du LLM Aspose. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crée une instance du client Web Aspose AI qui se connecte au point de terminaison par défaut du LLM Aspose en utilisant un  HttpURLConnection  géré à l’extérieur. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crée une instance du client Web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client Web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpURLConnection  géré à l’extérieur. |

## Méthodes

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envoie une instruction de chat au modèle d’IA et renvoie le message de réponse à l’instruction donnée. |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [dispose()](#dispose--) | Libère les ressources utilisées par cette instance. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crée une instance du client Web Aspose AI qui se connecte au point de terminaison par défaut du LLM Aspose. C’est le client utilisé par le constructeur sans paramètres  SlidesAIAgent() , donc le créer explicitement n’est requis que lorsque le client est passé directement au constructeur  SlidesAIAgent(IAIWebClient) .

```
AsposeAIWebClient aiClient = new AsposeAIWebClient();
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
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Crée une instance du client Web Aspose AI qui se connecte au point de terminaison par défaut du LLM Aspose en utilisant un  HttpURLConnection  géré à l’extérieur. Le  HttpURLConnection  fourni n’est pas libéré par cette instance et reste la propriété de l’appelant.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpURLConnection  gérée à l’extérieur.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
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

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Crée une instance du client Web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. Utilisez cette surcharge lorsque vous disposez d’une URL fournie par l’équipe Aspose.Slides ; sinon, utilisez la surcharge  AsposeAIWebClient()  avec l’URL par défaut.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l’équipe Aspose.Slides.

```
AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl);
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

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Crée une instance du client Web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpURLConnection  géré à l’extérieur. Le  HttpURLConnection  fourni n’est pas libéré par cette instance et reste la propriété de l’appelant. Utilisez cette surcharge lorsque vous avez une URL fournie par l’équipe Aspose.Slides et que vous souhaitez fournir votre propre  HttpURLConnection ; si vous avez seulement besoin de votre propre  HttpURLConnection  avec l’URL par défaut, utilisez la surcharge  AsposeAIWebClient(HttpURLConnection)  à la place.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l’équipe Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpURLConnection  gérée à l’extérieur.

```
URL url = new URL(url);
 HttpURLConnection httpClient = (HttpURLConnection) url.openConnection();
 try {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
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

Envoie une instruction de chat au modèle d’IA et renvoie le message de réponse à l’instruction donnée.

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L’instruction ou le message à traiter par le modèle d’IA. |

**Renvoie:**
java.lang.String - Le message généré par le modèle d’IA en réponse à l’instruction donnée.

### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels d’IA classiques, les conversations conservent l’ensemble du contexte.

**Renvoie:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).

### dispose() {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées par cette instance.