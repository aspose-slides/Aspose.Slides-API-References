---
title: IAIWebClient
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Interfejs klienta AI Web.
type: docs
url: /pl/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Interfejs klienta AI Web. Ten interfejs umożliwia zastąpienie różnych modeli językowych AI. Klasy implementujące ten interfejs powinny być używane razem z SlidesAIAgent.
## Metody

| Metoda | Opis |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Wysyła instrukcję czatu do modelu AI przy użyciu dostarczonej instancji HttpConnection i zwraca wiadomość odpowiedzi na podaną instrukcję. |
| [createConversation()](#createConversation--) | Tworzy instancję konwersacji. |
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

Tworzy instancję konwersacji. W przeciwieństwie do standardowych wywołań AI, konwersacje zachowują cały kontekst.

**Zwraca:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - An [IAIConversation](../../com.aspose.slides/iaiconversation) instance.