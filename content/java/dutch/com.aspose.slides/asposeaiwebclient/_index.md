---
title: AsposeAIWebClient
second_title: Aspose.Slides voor Java API Referentie
description: Een ingebouwde  implementatie die verbinding maakt met Asposes eigen LLM.
type: docs
url: /nl/com.aspose.slides/asposeaiwebclient/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAIWebClient](../../com.aspose.slides/iaiwebclient), com.aspose.ms.System.IDisposable
```
public final class AsposeAIWebClient implements IAIWebClient, System.IDisposable
```

Een ingebouwde [IAIWebClient](../../com.aspose.slides/iaiwebclient) implementatie die verbinding maakt met Aspose's eigen LLM. Dit is de standaardclient die wordt gebruikt door de parameterloze  SlidesAIAgent()  constructor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AsposeAIWebClient()](#AsposeAIWebClient--) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt. |
| [AsposeAIWebClient(HttpURLConnection httpClient)](#AsposeAIWebClient-java.net.HttpURLConnection-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt met behulp van een extern beheerde  HttpURLConnection . |
| [AsposeAIWebClient(String url)](#AsposeAIWebClient-java.lang.String-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL. |
| [AsposeAIWebClient(String url, HttpURLConnection httpClient)](#AsposeAIWebClient-java.lang.String-java.net.HttpURLConnection-) | Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL met behulp van een extern beheerde  HttpURLConnection . |
## Methods

| Method | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Stuur een chat-instructie naar het AI-model en retourneert een responsbericht voor de gegeven instructie. |
| [createConversation()](#createConversation--) | Maakt een conversatie-instantie. |
| [dispose()](#dispose--) | Vrijgeeft de door deze instantie gebruikte bronnen. |
### AsposeAIWebClient() {#AsposeAIWebClient--}
```
public AsposeAIWebClient()
```

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt. Dit is de client die wordt gebruikt door de parameterloze  SlidesAIAgent()  constructor, dus expliciet aanmaken is alleen nodig wanneer de client rechtstreeks wordt doorgegeven aan de  SlidesAIAgent(IAIWebClient)  constructor.

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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met het standaard Aspose LLM-eindpunt met behulp van een extern beheerde  HttpURLConnection . De meegegeven  HttpURLConnection  wordt niet door deze instantie vrijgegeven en blijft eigendom van de aanroeper.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| httpClient | java.net.HttpURLConnection | Een extern beheerde  HttpURLConnection  instantie.

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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL. Gebruik deze overload wanneer je een URL hebt die door het Aspose.Slides-team wordt geleverd; anders gebruik je de  AsposeAIWebClient()  overload met de standaard-URL.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | Eindpunt-URL van de Aspose LLM, geleverd door het Aspose.Slides-team.

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

Maakt een instantie van de Aspose AI-webclient die verbinding maakt met een aangepaste eindpunt-URL met behulp van een extern beheerde  HttpURLConnection . De meegegeven  HttpURLConnection  wordt niet door deze instantie vrijgegeven en blijft eigendom van de aanroeper. Gebruik deze overload wanneer je een URL hebt die door het Aspose.Slides-team is geleverd en je je eigen  HttpURLConnection wilt leveren; als je alleen je eigen  HttpURLConnection nodig hebt met de standaard-URL, gebruik dan de  AsposeAIWebClient(HttpURLConnection)  overload.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | Eindpunt-URL van de Aspose LLM, geleverd door het Aspose.Slides-team. |
| httpClient | java.net.HttpURLConnection | Een extern beheerde  HttpURLConnection  instantie.

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

Stuurt een chat-instructie naar het AI-model en retourneert een responsbericht voor de gegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retour:**
java.lang.String - Het bericht dat door het AI-model wordt gegenereerd als reactie op de gegeven instructie.
### createConversation() {#createConversation--}
```
public final IAIConversation createConversation()
```

Maakt een conversatie-instantie. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.

**Retour:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation) instantie.
### dispose() {#dispose--}
```
public final void dispose()
```

Vrijgeeft de door deze instantie gebruikte bronnen.