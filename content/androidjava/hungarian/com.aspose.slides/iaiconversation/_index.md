---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Egy beszélgetéspéldányt reprezentál.
type: docs
url: /hu/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Egy beszélgetéspéldányt reprezentál. A hagyományos AI hívásoktól eltérően a beszélgetések megőrzik a teljes kontextust.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Küld egy beszélgetési kérést tartalmazó üzenetet a teljes kontextussal, és visszaadja a választ. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Küld egy beszélgetési kérést tartalmazó üzenetet a teljes kontextussal, és visszaadja a választ.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| instruction | java.lang.String | Az utasítás vagy üzenet, amelyet az AI modell feldolgoz. |

**Visszatérési érték:**
java.lang.String - Az AI modell által a megadott utasításra a beszélgetési kontextusban generált üzenet.