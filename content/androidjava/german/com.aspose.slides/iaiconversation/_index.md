---
title: IAIConversation
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt eine Gesprächsinstanz dar.
type: docs
url: /de/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Stellt eine Gesprächsinstanz dar. Im Gegensatz zu regulären KI-Aufrufen behalten Gespräche den gesamten Kontext bei.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Sendet eine Konversationsanforderungsnachricht inklusive des gesamten Kontexts und gibt die Antwort zurück. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Sendet eine Konversationsanforderungsnachricht inklusive des gesamten Kontexts und gibt die Antwort zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String | Die Anweisung oder Nachricht, die vom KI-Modell verarbeitet werden soll. |

**Rückgabewert:**
java.lang.String - Die vom KI-Modell erzeugte Nachricht als Antwort auf die gegebene Anweisung im Kontext des Gesprächs.