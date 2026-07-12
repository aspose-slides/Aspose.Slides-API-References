---
title: IAIWebClient
second_title: Aspose.Slides for Android via Java API Reference
description: AI Web client interface.
type: docs
url: /hu/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web kliens interfész. Ez az interfész lehetővé teszi különböző AI nyelvi modellek cseréjét. Az interfészt megvalósító osztályoknak a SlidesAIAgent-tel együtt kell használniuk.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Chat utasítást küld az AI modellnek egy megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet az adott utasításra. |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Chat utasítást küld az AI modellnek egy megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet az adott utasításra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet. |

**Visszatérési érték:**
java.lang.String - Az AI modell által az adott utasításra generált üzenet.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Létrehoz egy beszélgetés példányt. A szokásos AI hívásoktól eltérően a beszélgetések megtartják az egész kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.