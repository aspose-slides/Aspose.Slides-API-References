---
title: IBlurEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který představuje efekt Blur aplikovaný na celý tvar, včetně jeho výplně.
type: docs
url: /cs/com.aspose.slides/iblureffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt Blur aplikovaný na celý tvar, včetně jeho výplně. Všechny barevné kanály, včetně alfa, jsou ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Vrací nebo nastavuje poloměr rozostření. |
| [getGrow()](#getGrow--) | Určuje, zda mají být ohraničení objektu zvětšena v důsledku rozostření. |
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

Určuje, zda mají být ohraničení objektu zvětšena v důsledku rozostření. Hodnota true znamená, že ohraničení jsou zvětšena, zatímco false značí, že nejsou. Pouze pro čtení boolean.

**Vrací:**
boolean