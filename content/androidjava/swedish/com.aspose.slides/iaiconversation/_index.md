---
title: IAIConversation
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en konversationsinstans.
type: docs
url: /sv/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Representerar en konversationsinstans. Till skillnad från vanliga AI-anrop behåller konversationer hela sammanhanget.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Skickar konversationsförfrågningsmeddelande inklusive hela sammanhanget och returnerar svar. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Skickar konversationsförfrågningsmeddelande inklusive hela sammanhanget och returnerar svar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| instruction | java.lang.String | Instruktionen eller meddelandet som ska bearbetas av AI-modellen. |

**Returnerar:**
java.lang.String - Meddelandet som genereras av AI-modellen som svar på den givna instruktionen inom konversationssammanhanget.