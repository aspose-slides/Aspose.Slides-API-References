---
title: ITemplateEngine
second_title: Aspose.Slides a Java API referencia
description: Egy sablonmotor, amely a sablon és az adatok párját a kimeneti eredményre, általában HTML-re alakítja.
type: docs
url: /hu/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Egy sablonmotor, amely a sablon és az adatok párját a kimeneti eredményre (általában HTML) alakítja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Hozzáadja a sablont a sablongyűjteményhez. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Átalakítja a sablont a megadott kulccsal és modellobjektummal a kimenetre. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Hozzáadja a sablont a sablongyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | A sablon kulcsa a sablongyűjteményben. |
| template | java.lang.String | A sablon tartalma. |
| modelType | com.aspose.ms.System.Type | A sablon modellobjektumának típusa. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Átalakítja a sablont a megadott kulccsal és modellobjektummal a kimenetre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | java.lang.String | A sablon kulcsa a sablongyűjteményben. |
| model | java.lang.Object | Modellobjektum, amely adatokat tartalmaz az átalakításhoz. |

**Visszatérési érték:**
java.lang.String - A kapott kimenet Stringként.