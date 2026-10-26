---
title: AsposeAIWebClient
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Une implémentation intégrée qui se connecte au LLM propriétaire d'Aspose.
type: docs
url: /fr/com.aspose.slides/asposeaiwebclient/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable  
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) intégrée qui se connecte au LLM propriétaire d'Aspose. C’est le client par défaut utilisé par le constructeur sans paramètres  SlidesAIAgent()  constructeur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut en utilisant un  HttpURLConnection  géré en externe. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpURLConnection  géré en externe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Envoie une instruction de chat au modèle IA et renvoie le message de réponse à l'instruction donnée. |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [dispose()](#dispose--) | Libère les ressources utilisées par cette instance. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut. C’est le client utilisé par le constructeur sans paramètres  SlidesAIAgent()  , il n’est donc nécessaire de le créer explicitement que lorsqu’on transmet le client directement au constructeur  SlidesAIAgent(IAIWebClient) .
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

Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM Aspose par défaut en utilisant un  HttpURLConnection  géré en externe. Le  HttpURLConnection  fourni n’est pas libéré par cette instance et reste la propriété de l’appelant.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpURLConnection  gérée en externe. |
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

Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. Utilisez cette surcharge lorsque vous disposez d’une URL fournie par l’équipe Aspose.Slides ; sinon, utilisez la surcharge  AsposeAIWebClient()  avec l’URL par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l’équipe Aspose.Slides. |
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

Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpURLConnection  géré en externe. Le  HttpURLConnection  fourni n’est pas libéré par cette instance et reste la propriété de l’appelant. Utilisez cette surcharge lorsque vous avez une URL fournie par l’équipe Aspose.Slides et que vous souhaitez fournir votre propre  HttpURLConnection ; si vous avez seulement besoin de votre propre  HttpURLConnection avec l’URL par défaut, utilisez la surcharge  AsposeAIWebClient(HttpURLConnection)  à la place.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l’équipe Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpURLConnection  gérée en externe. |
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

Envoie une instruction de chat au modèle IA et renvoie le message de réponse à l’instruction donnée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | L’instruction ou le message à traiter par le modèle IA. |

**Retour:**
java.lang.String - Le message généré par le modèle IA en réponse à l’instruction donnée.
### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels IA classiques, les conversations conservent tout le contexte.

**Retour:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une [IAIConversation](../../com.aspose.slides/iaiconversation) instance.
### dispose() {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées par cette instance.