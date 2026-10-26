---
title: IMathBar
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Spécifie la fonction de barre composée d'un argument de base et d'une barre supérieure ou inférieure
type: docs
url: /fr/com.aspose.slides/imathbar/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

Spécifie la fonction de barre, composée d’un argument de base et d’une barre supérieure ou inférieure

--------------------

> ```
> Exemple:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getPosition()](#getPosition--) | Position of the bar line. |
| [setPosition(int value)](#setPosition-int-) | Position of the bar line. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument de base

--------------------

> ```
> Exemple:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Position de la ligne de la barre. Valeur par défaut : Top

--------------------

> ```
> Exemple:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
>  ```

**Renvoie:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)

Position de la ligne de la barre. Valeur par défaut : Top

--------------------

> ```
> Exemple:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |