---
title: ITabEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui contient les propriétés d'arrêt de tabulation des textes effectifs.
type: docs
url: /fr/com.aspose.slides/itabeffectivedata/
---
**Toutes les interfaces implémentées :**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Objet immuable qui contient les propriétés d'arrêt de tabulation du texte effectif.

--------------------

Cette interface est utilisée comme partie de [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Returns position of a tab. |
| [getAlignment()](#getAlignment--) | Returns align style of a tab. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Renvoie la position d'une tabulation. L'affectation de cette propriété peut modifier l'index de la tabulation dans la collection et invalider l'énumérateur. Lecture seule double.

**Retour :**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Renvoie le style d'alignement d'une tabulation. Lecture seule [TabAlignment](../../com.aspose.slides/tabalignment).

**Retour :**
int