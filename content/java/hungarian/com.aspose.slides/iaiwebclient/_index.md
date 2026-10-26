---
title: IAIWebClient
second_title: Aspose.Slides for Java API referencia
description: AI Web kliens interfész.
type: docs
url: /hu/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

AI Web kliens interfész. Ez az interfész lehetővé teszi különböző AI nyelvi modellek helyettesítését. Az interfészt megvalósító osztályoknak a SlidesAIAgent-tel együtt kell használni.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Chatutasítást küld az AI modellnek a megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet a megadott instrukcióra. |
| [createConversation()](#createConversation--) | Létrehoz egy beszélgetés példányt. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```


Chatutasítást küld az AI modellnek a megadott HttpConnection példány használatával, és visszaadja a válaszüzenetet a megadott instrukcióra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó instrukció vagy üzenet. |

**Visszatérési érték:**
java.lang.String - A megadott instrukcióra válaszul az AI modell által generált üzenet.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```


Létrehoz egy beszélgetés példányt. A szokásos AI hívásoktól eltérően a beszélgetések megtartják a teljes kontextust.

**Visszatérési érték:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Egy [IAIConversation](../../com.aspose.slides/iaiconversation) példány.