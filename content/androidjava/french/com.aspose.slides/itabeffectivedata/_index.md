---
title: ITabEffectiveData
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Objet immutable qui contient les propriétés de tabulation des textes effectifs.
type: docs
url: /fr/com.aspose.slides/itabeffectivedata/
---
**Toutes les interfaces implémentées :**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Objet immutable qui contient les propriétés de tabulation du texte effectif.

--------------------

Cette interface est utilisée comme partie de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Renvoie la position d’une tabulation. |
| [getAlignment()](#getAlignment--) | Renvoie le style d’alignement d’une tabulation. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Renvoie la position d’une tabulation. L’affectation de cette propriété peut modifier l’indice de la tabulation dans la collection et invalider l’Enumerator. Lecture seule double.

**Renvoie :**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Renvoie le style d’alignement d’une tabulation. Lecture seule [TabAlignment](../../com.aspose.slides/tabalignment).

**Renvoie :**
int