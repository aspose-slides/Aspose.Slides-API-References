---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides pro Android přes Java API Reference
description: Neměnný objekt, který představuje efekt Alpha Bi-Level.
type: docs
url: /cs/com.aspose.slides/ialphabileveleffectivedata/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt Alpha Bi-Level. Hodnoty Alpha (průhlednost) menší než práh jsou změněny na 0 (zcela průhledné) a hodnoty Alpha větší nebo rovny prahu jsou změněny na 100 % (zcela neprůhledné).
## Metody

| Metoda | Popis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Vrací práh efektu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Vrací práh efektu. Pouze pro čtení float.

**Vrací:**
float