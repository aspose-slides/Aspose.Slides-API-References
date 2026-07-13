---
title: ITemplateEngine
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en mallmotor som omvandlar mall- och datapar till resulterande utdata, vanligtvis HTML.
type: docs
url: /sv/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Representerar en mallmotor som omvandlar mall- och datapar till resulterande utdata (vanligtvis HTML).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Lägger till mallen i mallsamlingen. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Omvandlar mallen med den angivna nyckeln och modellobjektet till utdata. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Lägger till mallen i mallsamlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för mallen i mallsamlingen. |
| template | java.lang.String | Mallens innehåll. |
| modelType | com.aspose.ms.System.Type | Typ av modellobjekt för mallen. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Omvandlar mallen med den angivna nyckeln och modellobjektet till utdata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key | java.lang.String | Nyckel för mallen i mallsamlingen. |
| model | java.lang.Object | Modellobjekt med data för omvandling. |

**Returnerar:**
java.lang.String - Resulterande utdata som en sträng.