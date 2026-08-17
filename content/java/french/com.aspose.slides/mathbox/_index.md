---
title: MathBox
second_title: Référence API Aspose.Slides pour Java
description: Spécifie l'emballage logique d'un élément mathématique.
type: docs
url: /fr/com.aspose.slides/mathbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Spécifie l'encapsulation logique (emballage) d'un élément mathématique. Par exemple, un objet encapsulé peut servir d'émulateur d'opérateur avec ou sans point d'alignement, servir de point de rupture de ligne, ou être groupé de façon à ne pas autoriser les ruptures de ligne à l'intérieur. Par exemple, l'opérateur "==" doit être encapsulé pour empêcher les ruptures de ligne.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initialise MathBox avec l'élément spécifié comme argument |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument de base |
| [getOperatorEmulator()](#getOperatorEmulator--) | Émulateur d'opérateur. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Émulateur d'opérateur. |
| [getNoBreak()](#getNoBreak--) | Pas de rupture Cette propriété spécifie la propriété "unbreakable" sur la boîte d'objet. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Pas de rupture Cette propriété spécifie la propriété "unbreakable" sur la boîte d'objet. |
| [getDifferential()](#getDifferential--) | Différentiel Lorsque vrai, la boîte agit comme un différentiel (par ex., \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Différentiel Lorsque vrai, la boîte agit comme un différentiel (par ex., \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. |
| [getExplicitBreak()](#getExplicitBreak--) | Rupture explicite spécifie s'il y a une rupture de ligne au début de l'objet Box, de façon que la ligne se déroule au début de l'objet box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Rupture explicite spécifie s'il y a une rupture de ligne au début de l'objet Box, de façon que la ligne se déroule au début de l'objet box. |
| [getChildren()](#getChildren--) | Obtient les éléments enfants |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Initialise MathBox avec l'élément spécifié comme argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'élément de base auquel la boîte est appliquée. Peut être nul. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument de base

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Renvoie :**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, comme '=='. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Renvoie :**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Émulateur d'opérateur. Lorsque vrai, la boîte et son contenu se comportent comme un seul opérateur et héritent des propriétés d'un opérateur. Cela signifie, par exemple, que le caractère peut servir de point de rupture de ligne et peut être aligné avec d'autres opérateurs. Les émulateurs d'opérateur sont souvent utilisés lorsque un ou plusieurs glyphes se combinent pour former un opérateur, comme '=='. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Pas de rupture Cette propriété spécifie la propriété "unbreakable" sur la boîte d'objet. Lorsque vrai, aucune rupture de ligne ne peut survenir à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent survenir à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Renvoie :**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Pas de rupture Cette propriété spécifie la propriété "unbreakable" sur la boîte d'objet. Lorsque vrai, aucune rupture de ligne ne peut survenir à l'intérieur de la boîte. Cela peut être important pour les émulateurs d'opérateur qui comprennent plus d'un opérateur binaire. Lorsque cet élément n'est pas spécifié, des ruptures peuvent survenir à l'intérieur de la boîte. Valeur par défaut : true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Différentiel Lorsque vrai, la boîte agit comme un différentiel (par ex., \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false

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
public final void setDifferential(boolean value)
```


Différentiel Lorsque vrai, la boîte agit comme un différentiel (par ex., \\ud835\\udc51\\ud835\\udc65 dans un intégrande), et reçoit l'espacement horizontal approprié pour le différentiel mathématique. Valeur par défaut : false

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
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```


Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Renvoie :**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Lorsque vrai, cet émulateur d'opérateur sert de point d'alignement ; c'est-à-dire, les points d'alignement désignés dans d'autres équations peuvent être alignés avec lui. Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```


Rupture explicite spécifie s'il y a une rupture de ligne au début de l'objet Box, de façon que la ligne se déroule au début de l'objet box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Renvoie :**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Rupture explicite spécifie s'il y a une rupture de ligne au début de l'objet Box, de façon que la ligne se déroule au début de l'objet box. Spécifie le numéro de l'opérateur sur la ligne précédente du texte mathématique qui doit être utilisé comme point d'alignement pour la ligne actuelle du texte mathématique. Valeurs possibles : 1..255 Valeur par défaut : 0 (pas de rupture explicite)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtient les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriétés du caractère de contrôle

**Renvoie :**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps