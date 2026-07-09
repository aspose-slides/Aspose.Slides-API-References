---
title: IPortionFactory
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Permet de créer des portions de test
type: docs
url: /fr/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Permet de créer des portions de test

--------------------

Pour la compatibilité COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createPortion()](#createPortion--) | Crée une portion de texte vide. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Crée une portion de texte à partir d'une chaîne spécifiée. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Crée une portion en utilisant les données d'une portion spécifiée. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Crée une portion de texte vide.

**Valeur de retour:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Crée une portion de texte à partir d'une chaîne spécifiée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| str | java.lang.String | Chaîne. |

**Valeur de retour:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Crée une portion en utilisant les données d'une portion spécifiée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Une portion à utiliser. |

**Valeur de retour:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.