---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: AI-Web-Client-Schnittstelle.
type: docs
url: /de/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI-Web-Client-Schnittstelle. Dieses Interface ermöglicht den Austausch verschiedener KI-Sprachmodelle. Klassen, die dieses Interface implementieren, sollen zusammen mit SlidesAIAgent verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer bereitgestellten HttpConnection-Instanz und gibt die Antwortnachricht zur angegebenen Anweisung zurück. |
| [createConversation()](#createConversation--) | Erstellt eine Konversationsinstanz. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Sendet eine Chat-Anweisung an das KI-Modell unter Verwendung einer bereitgestellten HttpConnection-Instanz und gibt die Antwortnachricht zur angegebenen Anweisung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| instruction | java.lang.String | Die Anweisung oder Nachricht, die vom KI-Modell verarbeitet werden soll. |

**Rückgabewert:**
java.lang.String - Die vom KI-Modell erzeugte Nachricht als Antwort auf die angegebene Anweisung.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Erstellt eine Konversationsinstanz. Im Gegensatz zu regulären KI-Aufrufen behalten Unterhaltungen den gesamten Kontext.

**Rückgabewert:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Eine [IAIConversation](../../com.aspose.slides/iaiconversation) Instanz.