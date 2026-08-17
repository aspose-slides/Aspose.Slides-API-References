---
title: IMathBox
second_title: Référence API Aspose.Slides for Java
description: Spécifie l'emballage logique (boxing) d'un élément mathématique.
type: docs
url: /fr/com.aspose.slides/imathbox/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Spécifie l'encapsulation logique (emballage) d'un élément mathématique. Par exemple, un objet encadré peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de saut de ligne, ou être groupé de sorte à ne pas autoriser les sauts de ligne à l'intérieur. Par exemple, l'opérateur "==" doit être encadré pour empêcher les sauts de ligne.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Méthodes

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Émulateur d'opérateur. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Émulateur d'opérateur. |
| [getNoBreak()](#getNoBreak--) | Pas de rupture. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Pas de rupture. |
| [getDifferential()](#getDifferential--) | Différentiel. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Différentiel. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c’est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c’est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. |
| [getExplicitBreak()](#getExplicitBreak--) | La rupture explicite indique s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne se replie au début de l'objet box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | La rupture explicite indique s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne se replie au début de l'objet box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument de base

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
>  ```


**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, comme '=='. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Renvoie :**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de saut de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, comme '=='. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Pas de rupture. Cette propriété spécifie la propriété « incassable » de la boîte d'objet. Lorsque vrai, aucun saut de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comportent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des sauts peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Renvoie :**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Pas de rupture. Cette propriété spécifie la propriété « incassable » de la boîte d'objet. Lorsque vrai, aucun saut de ligne ne peut se produire à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comportent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des sauts peuvent se produire à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Différentiel. Lorsque vrai, la boîte agit comme un différentiel (par exemple, \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Renvoie :**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Différentiel. Lorsque vrai, la boîte agit comme un différentiel (par exemple, \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c’est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false

--------------------

> ```
> Exemple:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Renvoie :**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c’est-à-dire que les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

La rupture explicite indique s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne se replie au début de l'objet box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)

--------------------

> ```
> Exemple:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Renvoie :**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

La rupture explicite indique s'il y a un saut de ligne au début de l'objet Box, de sorte que la ligne se replie au début de l'objet box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)

--------------------

> ```
> Exemple:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```


**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |