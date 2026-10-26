---
title: IBlur
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje efekt rozostření, který se použije na celý tvar včetně jeho výplně.
type: docs
url: /cs/com.aspose.slides/iblur/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Představuje efekt rozmazání, který se použije na celý tvar, včetně jeho výplně. Všechny barevné kanály, včetně alfy, jsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozmazání. |
| [setRadius(double value)](#setRadius-double-) | Vrací nebo nastavuje poloměr rozmazání. |
| [getGrow()](#getGrow--) | Určuje, zda by měly být mezery objektu rozšířeny v důsledku rozmazání. |
| [setGrow(boolean value)](#setGrow-boolean-) | Určuje, zda by měly být mezery objektu rozšířeny v důsledku rozmazání. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Vrací nebo nastavuje poloměr rozmazání. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Vrací nebo nastavuje poloměr rozmazání. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Určuje, zda by měly být mezery objektu rozšířeny v důsledku rozmazání. True označuje, že jsou rozšířeny, zatímco false označuje, že nejsou. Čtení/zápis boolean.

**Vrací:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Určuje, zda by měly být mezery objektu rozšířeny v důsledku rozmazání. True označuje, že jsou rozšířeny, zatímco false označuje, že nejsou. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |