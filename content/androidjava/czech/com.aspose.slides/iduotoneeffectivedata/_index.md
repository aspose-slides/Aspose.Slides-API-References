---
title: IDuotoneEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který představuje efekt duotonu.
type: docs
url: /cs/com.aspose.slides/iduotoneeffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt duotonu. Pro každý pixel kombinuje clr1 a clr2 pomocí lineární interpolace, aby určil novou barvu tohoto pixelu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor1()](#getColor1--) | Vrací cílový formát barvy pro tmavé pixely. |
| [getColor2()](#getColor2--) | Vrací cílový formát barvy pro světlé pixely. |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```


Vrací cílový formát barvy pro tmavé pixely. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```


Vrací cílový formát barvy pro světlé pixely. Pouze pro čtení java.lang.Integer.

**Vrací:**
java.lang.Integer