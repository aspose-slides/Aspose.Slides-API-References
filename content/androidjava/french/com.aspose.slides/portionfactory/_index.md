---
title: PortionFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer des portions de test
type: docs
url: /fr/com.aspose.slides/portionfactory/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
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

**Renvoie:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Crée une portion de texte à partir d'une chaîne spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Renvoie:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Crée une portion en utilisant les données d'une portion spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**Renvoie:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.