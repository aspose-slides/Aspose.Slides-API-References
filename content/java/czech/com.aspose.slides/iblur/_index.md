---
title: IBlur
second_title: Aspose.Slides pro Java API Reference
description: Představuje efekt rozostření, který se aplikuje na celý tvar včetně výplně.
type: docs
url: /cs/com.aspose.slides/iblur/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Představuje efekt rozostření, který se aplikuje na celý tvar, včetně výplně. Všechny barevné kanály, včetně alfa, jsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozostření. |
| [setRadius(double value)](#setRadius-double-) | Vrací nebo nastavuje poloměr rozostření. |
| [getGrow()](#getGrow--) | Určuje, zda by měly být hranice objektu zvětšeny v důsledku rozostření. |
| [setGrow(boolean value)](#setGrow-boolean-) | Určuje, zda by měly být hranice objektu zvětšeny v důsledku rozostření. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Vrací nebo nastavuje poloměr rozostření. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Vrací nebo nastavuje poloměr rozostření. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Určuje, zda by měly být hranice objektu zvětšeny v důsledku rozostření. True označuje, že jsou hranice zvětšeny, zatímco false označuje, že nejsou. Čtení/zápis boolean.

**Vrací:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Určuje, zda by měly být hranice objektu zvětšeny v důsledku rozostření. True označuje, že jsou hranice zvětšeny, zatímco false označuje, že nejsou. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |