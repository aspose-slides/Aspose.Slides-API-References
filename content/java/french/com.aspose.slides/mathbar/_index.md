---
title: MathBar
second_title: Référence API Aspose.Slides pour Java
description: Spécifie la fonction de barre composée d'un argument de base et d'une barre supérieure ou inférieure
type: docs
url: /fr/com.aspose.slides/mathbar/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Spécifie la fonction de barre, composée d'un argument de base et d'une barre supérieure ou inférieure

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Initialise MathBar avec une barre supérieure (position Haut) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Initialise MathBar avec la position spécifiée |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getPosition()](#getPosition--) | Position de la ligne de la barre. |
| [setPosition(int value)](#setPosition-int-) | Position de la ligne de la barre. |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés des caractères de contrôle |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

Initialise MathBar avec une barre supérieure (position Haut)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la barre est appliquée |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

Initialise MathBar avec la position spécifiée

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la barre est appliquée |
| position | int | Position de la ligne de la barre. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argument de base

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Renvoie:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Position de la ligne de la barre. Valeur par défaut : Haut

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Renvoie:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Position de la ligne de la barre. Valeur par défaut : Haut

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Renvoie:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés des caractères de contrôle

**Renvoie:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps