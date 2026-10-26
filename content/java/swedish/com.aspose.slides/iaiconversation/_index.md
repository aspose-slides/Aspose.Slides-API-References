---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Representerar en konversationsinstans.
type: docs
url: /sv/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Representerar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela kontexten.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Skickar konversationsbegäran inklusive hela kontexten och returnerar svar. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Skickar konversationsbegäran inklusive hela kontexten och returnerar svar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen. |

**Returnerar:**
java.lang.String - Meddelandet som genereras av AI-modellen som svar på den givna instruktionen inom konversationskontexten.