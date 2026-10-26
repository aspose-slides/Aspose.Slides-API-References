---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.
type: docs
url: /fr/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.
## Méthodes

| Méthode | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Résout l'URI absolu à partir des URI de base et relatifs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Mappe un URI vers un objet contenant la ressource réelle. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Résout l'URI absolu à partir des URI de base et relatifs.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI de base des objets de liaison |
| relativeUri | java.lang.String | URI relatif vers l'objet lié. |

**Valeur de retour :**
java.lang.String - URI absolu ou null si l'URI relatif ne peut pas être résolu.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Mappe un URI vers un objet contenant la ressource réelle.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolu vers l'objet. |

**Valeur de retour :**
java.io.InputStream - Un objet InputStream ou null si la ressource ne peut pas être diffusée.