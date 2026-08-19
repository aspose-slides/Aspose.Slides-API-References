---
title: IBlurEffectiveData
second_title: Aspose.Slides pro Java API Reference
description: Neměnný objekt, který představuje efekt rozostření aplikovaný na celý tvar včetně jeho výplně.
type: docs
url: /cs/com.aspose.slides/iblureffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt rozostření aplikovaný na celý tvar, včetně jeho výplně. Všechny barevné kanály, včetně alfa, jsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozostření. |
| [getGrow()](#getGrow--) | Určuje, zda by měly být ohraničení objektu rozšířeny v důsledku rozostření. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Vrací nebo nastavuje poloměr rozostření. Pouze pro čtení double.

**Vrací:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Určuje, zda by měly být ohraničení objektu rozšířeny v důsledku rozostření. Hodnota true značí, že ohraničení jsou rozšířena, zatímco false značí, že nejsou. Pouze pro čtení boolean.

**Vrací:**
boolean