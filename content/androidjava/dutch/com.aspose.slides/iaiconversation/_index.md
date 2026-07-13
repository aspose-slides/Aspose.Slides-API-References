---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /nl/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Vertegenwoordigt een gespreksexemplaar. In tegenstelling tot reguliere AI-aanroepen behouden gesprekken de volledige context.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Stuurt een gesprekverzoekbericht inclusief volledige context en retourneert een antwoord. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Stuurt een gesprekverzoekbericht inclusief volledige context en retourneert een antwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retourwaarde:**
java.lang.String - Het bericht dat door het AI-model wordt gegenereerd als reactie op de gegeven instructie binnen de gesprekscontext.