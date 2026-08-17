---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: Représente un moteur de modèles qui transforme une paire modèle et données en une sortie résultante généralement HTML.
type: docs
url: /fr/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

Représente un moteur de modèles qui transforme une paire modèle et données en une sortie résultante (généralement HTML).

## Méthodes

| Méthode | Description |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Ajoute le modèle à la collection de modèles. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforme le modèle avec la clé donnée et l'objet modèle en sortie. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

Ajoute le modèle à la collection de modèles.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clé du modèle dans la collection de modèles. |
| template | java.lang.String | Contenu du modèle. |
| modelType | com.aspose.ms.System.Type | Type d'un objet modèle pour le modèle. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

Transforme le modèle avec la clé donnée et l'objet modèle en sortie.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clé du modèle dans la collection de modèles. |
| model | java.lang.Object | Objet modèle contenant les données pour la transformation. |

**Retour:**
java.lang.String - Sortie résultante sous forme de chaîne.