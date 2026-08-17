---
title: OpenAIWebClient
second_title: Référence de l'API Aspose.Slides pour Java
description: Une implémentation intégrée qui se connecte à l'API OpenAI.
type: docs
url: /fr/com.aspose.slides/openaiwebclient/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), java.io.Closeable
```
public class OpenAIWebClient implements IAIWebClient, Closeable
```

Une implémentation intégrée [IAIWebClient](../../com.aspose.slides/iaiwebclient) qui se connecte à l'API OpenAI.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OpenAIWebClient(String model, String apiKey, String organizationId)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-) | Crée une instance du client web OpenAI. |
| [OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)](#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-) | Crée une instance du client web OpenAI qui utilise un HttpClient géré à l'extérieur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) |  |
| [createConversation()](#createConversation--) | Crée une instance de conversation. |
| [close()](#close--) | Libère les ressources utilisées par cette instance. |
### OpenAIWebClient(String model, String apiKey, String organizationId) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId)
```

Crée une instance du client web OpenAI.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Modèle de langage OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clé API OpenAI. |
| organizationId | java.lang.String | ID d'organisation (facultatif). |

```
using (OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null))
 {
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient) {#OpenAIWebClient-java.lang.String-java.lang.String-java.lang.String-java.net.HttpURLConnection-}
```
public OpenAIWebClient(String model, String apiKey, String organizationId, HttpURLConnection httpClient)
```

Crée une instance du client web OpenAI qui utilise un HttpClient géré à l'extérieur. Le HttpClient fourni n'est pas libéré par cette instance et reste la propriété de l'appelant.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| model | java.lang.String | Modèle de langage OpenAI. Valeurs possibles : - gpt-4o - gpt-4o-mini - o1 - o1-mini - o3 - o3-mini |
| apiKey | java.lang.String | Clé API OpenAI |
| organizationId | java.lang.String | ID d'organisation (facultatif) |
| httpClient | java.net.HttpURLConnection | Une instance de HttpClient gérée à l'extérieur |

```
using (HttpClient httpClient = new HttpClient())
 {
     OpenAIWebClient aiClient = new OpenAIWebClient("gpt-4o-mini", apiKey, null, httpClient);
     SlidesAIAgent aiAgent = new SlidesAIAgent(aiClient);
     using (Presentation presentation = new Presentation("Presentation.pptx"))
     {
         await aiAgent.TranslateAsync(presentation, "spanish");
         presentation.Save("translated.pptx", SaveFormat.Pptx);
     }
 }
``` |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public String callChat(String instruction)
```

Envoie une instruction de conversation au modèle d'IA en utilisant une instance HttpConnection fournie et renvoie le message de réponse à l'instruction donnée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String |  |

**Retourne :**
java.lang.String
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Crée une instance de conversation. Contrairement aux appels d'IA réguliers, les conversations conservent le contexte complet.

**Retourne :**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Une instance [IAIConversation](../../com.aspose.slides/iaiconversation).
### close() {#close--}
```
public final void close()
```

Libère les ressources utilisées par cette instance.