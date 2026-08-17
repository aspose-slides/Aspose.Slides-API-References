---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java Référence de l'API
description: Interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html et Svg.
type: docs
url: /fr/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Interface de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.
## Méthodes

| Méthode | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```


Résout l'URI absolu à partir des URI de base et relatifs.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI de base des objets liés |
| relativeUri | java.lang.String | URI relatif vers l'objet lié. |

**Retour :**
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

**Retour :**
java.io.InputStream - Un objet InputStream ou null si la ressource ne peut pas être diffusée.