---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI Web client interface.
type: docs
url: /nl/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web client interface. Deze interface maakt het mogelijk om verschillende AI-taalmodellen te vervangen. Klassen die deze interface implementeren, moeten samen met SlidesAIAgent worden gebruikt.
## Methods

| Method | Description |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Stuur een chatinstructie naar het AI-model met behulp van een opgegeven HttpConnection-instantie en retourneer het responsbericht voor de gegeven instructie. |
| [createConversation()](#createConversation--) | Maakt een conversatie-instantie. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Stuur een chatinstructie naar het AI-model met behulp van een opgegeven HttpConnection-instantie en retourneer het responsbericht voor de gegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retour:**
java.lang.String - Het bericht dat door het AI-model is gegenereerd als antwoord op de opgegeven instructie.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


Maakt een conversatie-instantie. In tegenstelling tot reguliere AI-aanroepen behouden conversaties de volledige context.

**Retour:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.