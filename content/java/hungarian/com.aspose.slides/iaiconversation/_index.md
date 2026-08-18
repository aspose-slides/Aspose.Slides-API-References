---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Egy beszélgetéspéldányt képvisel.
type: docs
url: /hu/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Egy beszélgetéspéldányt képvisel. A rendszeres AI hívásokkal ellentétben a beszélgetések megőrzik az egész kontextust.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Egy beszélgetési kérés üzenetet küld, amely tartalmazza az egész kontextust, és visszaadja a választ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Egy beszélgetési kérés üzenetet küld, amely tartalmazza az egész kontextust, és visszaadja a választ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instruction | java.lang.String | Az AI modell által feldolgozandó utasítás vagy üzenet. |

**Visszatérési érték:**
java.lang.String - A megadott utasításra a beszélgetési kontextusban az AI modell által generált üzenet.