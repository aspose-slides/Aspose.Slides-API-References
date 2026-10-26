---
title: Storage
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un stockage de données temporaire pour .
type: docs
url: /fr/com.aspose.slides/storage/
---
**Héritage:**
java.lang.Object
```
public final class Storage
```

Représente un stockage de données temporaire pour [WebDocument](../../com.aspose.slides/webdocument).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Place la valeur dans le stockage. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Récupère les données du stockage. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Détermine si le stockage contient un élément avec la clé spécifiée. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Place la valeur dans le stockage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clé de la valeur. |
| value | TValue | Valeur. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Récupère les données du stockage.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clé de la valeur. |

**Renvoie:**
TValue - Valeur de données si elle est présentée dans la collection de données, null sinon.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Détermine si le stockage contient un élément avec la clé spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Clé de la valeur. |

**Renvoie:**
boolean - True si le stockage contient un élément avec la clé spécifiée, false sinon.