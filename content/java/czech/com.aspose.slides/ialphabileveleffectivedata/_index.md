---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides pro Java – reference API
description: Neměnný objekt, který představuje efekt Alpha Bi-Level.
type: docs
url: /cs/com.aspose.slides/ialphabileveleffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Neměnný objekt, který představuje efekt Alpha Bi-Level. Hodnota Alpha (Opacity) menší než práh jsou změněny na 0 (zcela průhledné) a hodnoty alpha větší než nebo rovny prahu jsou změněny na 100 % (zcela neprůhledné).
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