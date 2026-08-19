---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Representeert een conversatie-instantie.
type: docs
url: /nl/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Representeert een conversatie-instantie. In tegenstelling tot reguliere AI-aanroepen behouden conversaties de volledige context.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Verzendt een gesprekverzoekbericht inclusief de volledige context en retourneert een reactie. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Verzendt een gesprekverzoekbericht inclusief de volledige context en retourneert een reactie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| instruction | java.lang.String | De instructie of het bericht dat door het AI-model moet worden verwerkt. |

**Retour:**
java.lang.String - Het bericht dat door het AI-model wordt gegenereerd als reactie op de gegeven instructie binnen de gesprekscontext.