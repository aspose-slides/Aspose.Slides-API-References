---
title: ExternalResourceResolver
second_title: Référence de l'API Aspose.Slides pour Java
description: Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html et Svg.
type: docs
url: /fr/com.aspose.slides/externalresourceresolver/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Classe de rappel utilisée pour résoudre les ressources externes lors de l'importation de documents Html, Svg.

--------------------

L'utilisation de ce résolveur peut créer une vulnérabilité lorsque le fichier HTML ou SVG fourni par le client permet au logiciel serveur d'obtenir un fichier local ou réseau. Utilisez-le avec prudence. Il est recommandé de ne pas spécifier ExternalResourceResolver du tout (seuls les objets intégrés seront lus) ou de créer une sous-classe qui vérifie si l'URI spécifiée est valide.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Résout l'URI absolu à partir des URI de base et relatif. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Associe un URI à un objet contenant la ressource réelle. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Résout l'URI absolu à partir des URI de base et relatif.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI de base des objets de liaison |
| relativeUri | java.lang.String | URI relatif vers l'objet lié. |

**Valeur de retour :**
java.lang.String - URI absolu ou null si l'URI relatif ne peut pas être résolu.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Associe un URI à un objet contenant la ressource réelle.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolu de l'objet. |

**Valeur de retour :**
java.io.InputStream - Un objet InputStream ou null si la ressource ne peut pas être lue.