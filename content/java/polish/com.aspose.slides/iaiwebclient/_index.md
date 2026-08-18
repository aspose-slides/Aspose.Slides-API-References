---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Interfejs klienta sieciowego AI.
type: docs
url: /pl/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interfejs klienta sieciowego AI. Ten interfejs umożliwia podstawienie różnych modeli językowych AI. Klasy implementujące ten interfejs powinny być używane razem z SlidesAIAgent.
## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sends a chat instruction to the AI model using a provided HttpConnection instance and return response message to the given instruction. |
| [createConversation()](#createConversation--) | Creates a conversation instance. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Wysyła instrukcję czatu do modelu AI przy użyciu dostarczonej instancji HttpConnection i zwraca wiadomość odpowiedzi na podaną instrukcję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukcja lub wiadomość do przetworzenia przez model AI. |

**Zwraca:**
java.lang.String - Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Tworzy instancję konwersacji. W przeciwieństwie do regularnych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Instancja [IAIConversation](../../com.aspose.slides/iaiconversation).