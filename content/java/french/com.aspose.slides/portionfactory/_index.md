---
title: PortionFactory
second_title: Référence de l'API Aspose.Slides pour Java
description: Permet de créer des portions de test
type: docs
url: /fr/com.aspose.slides/portionfactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Permet de créer des portions de test

--------------------

Pour la compatibilité COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [createPortion()](#createPortion--) | Crée une portion de texte vide. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crée une portion de texte à partir d'une chaîne spécifiée. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crée une portion en utilisant les données d'une portion spécifiée. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Crée une portion de texte vide.

**Retour :**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Crée une portion de texte à partir d'une chaîne spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Retour :**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Crée une portion en utilisant les données d'une portion spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Une portion à utiliser. |

**Retour :**
[IPortion](../../com.aspose.slides/iportion) - Portion.