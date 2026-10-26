---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje instancję konwersacji.
type: docs
url: /pl/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Reprezentuje instancję konwersacji. W przeciwieństwie do zwykłych wywołań AI, konwersacje zachowują cały kontekst.
## Metody

| Metoda | Opis |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Wysyła wiadomość żądania konwersacji, zawierającą cały kontekst i zwraca odpowiedź. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Wysyła wiadomość żądania konwersacji, zawierającą cały kontekst i zwraca odpowiedź.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| instruction | java.lang.String | Instrukcja lub wiadomość przetwarzana przez model AI. |

**Zwraca:**
java.lang.String - Wiadomość wygenerowana przez model AI w odpowiedzi na podaną instrukcję w kontekście konwersacji.