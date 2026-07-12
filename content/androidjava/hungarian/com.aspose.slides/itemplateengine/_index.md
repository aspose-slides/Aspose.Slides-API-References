---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: Egy sablonmotort reprezentál, amely a sablon- és adatpárt átalakítja a kapott kimenetté, általában HTML.
type: docs
url: /hu/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Egy sablonmotort reprezentál, amely a sablon- és adatpárt átalakítja a kapott kimenetté (általában HTML).

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Hozzáadja a sablont a sablongyűjteményhez. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Átalakítja a sablont a megadott kulccsal és modellobjektummal a kimenethez. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Hozzáadja a sablont a sablongyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | Kulcs a sablonhoz a sablongyűjteményben. |
| template | java.lang.String | Sablontartalom. |
| modelType | com.aspose.ms.System.Type | A modellobjektum típusa a sablonhoz. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Átalakítja a sablont a megadott kulccsal és modellobjektummal a kimenethez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | Kulcs a sablonhoz a sablongyűjteményben. |
| model | java.lang.Object | Modellobjektum az átalakításhoz szükséges adatokkal. |

**Visszatérési érték:**
java.lang.String - Az eredményül kapott kimenet Stringként.