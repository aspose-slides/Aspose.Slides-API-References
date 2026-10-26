---
title: IMathBar
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie la fonction de barre composée d'un argument de base et d'une barre supérieure ou inférieure
type: docs
url: /fr/com.aspose.slides/imathbar/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getPosition()](#getPosition--) | Position de la ligne de barre. |
| [setPosition(int value)](#setPosition-int-) | Position de la ligne de barre. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Retourne :**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Position de la ligne de barre. Valeur par défaut : Haut

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Retourne :**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Position de la ligne de barre. Valeur par défaut : Haut

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |