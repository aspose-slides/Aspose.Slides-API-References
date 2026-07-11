---
title: AsposeAIWebClient
second_title: Référence de l'API Aspose.Slides pour Java
description: Une implémentation  intégrée qui se connecte au LLM propre d'Aspose.
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

Une implémentation [IAIWebClient](../../com.aspose.slides/iaiwebclient) intégrée qui se connecte au LLM propre d'Aspose. C'est le client par défaut utilisé par le constructeur sans paramètres  SlidesAIAgent() .

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM par défaut d'Aspose. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM par défaut d'Aspose en utilisant un  HttpClient  géré de façon externe. |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpClient  géré de façon externe. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [dispose()](#dispose--) | Libère les ressources utilisées par cette instance. |

### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM par défaut d'Aspose. C'est le client utilisé par le constructeur sans paramètres  SlidesAIAgent() , donc le créer explicitement n'est nécessaire que lorsqu'on transmet le client directement au constructeur  SlidesAIAgent(IAIWebClient) .
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient())
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(HttpURLConnection httpClient) {#AsposeAIWebClient-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(HttpURLConnection httpClient)
```

Crée une instance du client web Aspose AI qui se connecte au point de terminaison LLM par défaut d'Aspose en utilisant un  HttpClient  géré de façon externe. Le  HttpClient  fourni n'est pas libéré par cette instance et reste la propriété de l'appelant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpClient  gérée de façon externe. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(String url) {#AsposeAIWebClient-java.lang.String-}
```
public AsposeAIWebClient(String url)
```

Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée. Utilisez cette surcharge lorsque vous disposez d'une URL fournie par l'équipe Aspose.Slides ; sinon, utilisez la surcharge  AsposeAIWebClient()  avec l'URL par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l'équipe Aspose.Slides. |
```
using (AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### AsposeAIWebClient(String url, HttpURLConnection httpClient) {#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-}
```
public AsposeAIWebClient(String url, HttpURLConnection httpClient)
```

Crée une instance du client web Aspose AI qui se connecte à une URL de point de terminaison personnalisée en utilisant un  HttpClient  géré de façon externe. Le  HttpClient  fourni n'est pas libéré par cette instance et reste la propriété de l'appelant. Utilisez cette surcharge lorsque vous avez une URL fournie par l'équipe Aspose.Slides et que vous souhaitez fournir votre propre  HttpClient ; si vous avez seulement besoin de votre propre  HttpClient  avec l'URL par défaut, utilisez la surcharge  AsposeAIWebClient(HttpClient)  à la place.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL du point de terminaison du LLM Aspose, fournie par l'équipe Aspose.Slides. |
| httpClient | java.net.HttpURLConnection | Une instance de  HttpClient  gérée de façon externe. |
```
using (HttpClient httpClient = new HttpClient())
 {
     AsposeAIWebClient aiClient = new AsposeAIWebClient(customUrl, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
```

### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envoie une instruction de chat au modèle d'IA en utilisant une instance HttpConnection fournie et renvoie le message de réponse à l'instruction donnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Renvoie :**
java.lang.String

### createConversation() {#createConversation--}
```
public final IIAConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels d'IA classiques, les conversations conservent l'intégralité du contexte.

**Renvoie :**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une [IAIConversation](../../com.aspose.slides/iaiconversation) instance.

### dispose() {#dispose--}
```
public final void dispose()
```

Libère les ressources utilisées par cette instance.