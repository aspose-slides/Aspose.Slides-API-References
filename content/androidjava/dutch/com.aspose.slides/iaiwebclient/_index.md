---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /nl/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web client interface. Deze interface maakt het mogelijk verschillende AI-taalmodellen te substitueren. Klassen die deze interface implementeren, moeten worden gebruikt samen met SlidesAIAgent.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Stuurt een chatinstructie naar het AI-model met behulp van een opgegeven HttpConnection-instantie en retourneert het responsbericht voor de opgegeven instructie. |
| [createConversation()](#createConversation--) | Maakt een conversatie-instantie. |

### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Stuurt een chatinstructie naar het AI-model met behulp van een opgegeven HttpConnection-instantie en retourneert het responsbericht voor de opgegeven instructie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retourneert:**
java.lang.String - De door het AI-model gegenereerde boodschap als reactie op de opgegeven instructie.

### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Maakt een conversatie-instantie. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.

**Retourneert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Een [IAIConversation](../../com.aspose.slides/iaiconversation) instantie.