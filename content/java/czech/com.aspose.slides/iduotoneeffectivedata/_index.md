---
title: IDuotoneEffectiveData
second_title: Aspose.Slides pro Java - reference API
description: Neměnný objekt, který představuje efekt Duotone.
type: docs
url: /cs/com.aspose.slides/iduotoneeffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt Duotone. Pro každý pixel kombinuje clr1 a clr2 pomocí lineární interpolace k určení nové barvy pro daný pixel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor1()](#getColor1--) | Vrací cílový formát barvy pro tmavé pixely. |
| [getColor2()](#getColor2--) | Vrací cílový formát barvy pro světlé pixely. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```

Vrací cílový formát barvy pro tmavé pixely. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```

Vrací cílový formát barvy pro světlé pixely. Pouze pro čtení java.awt.Color.

**Vrací:**
java.awt.Color