---
title: IBiLevelEffectiveData
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Neměnný objekt, který představuje dvoustupňový černobílý efekt.
type: docs
url: /cs/com.aspose.slides/ibileveleffectivedata/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Neproměnný objekt, který představuje dvoustupňový (černobílý) efekt. Vstupní barvy, jejichž luminance je menší než zadaná hodnota prahu, jsou změněny na černou. Vstupní barvy, jejichž luminance je větší nebo rovna zadané hodnotě, jsou nastaveny na bílou. Hodnoty alfa efektu nejsou tímto efektem ovlivněny.
## Metody

| Metoda | Popis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Vrací hodnotu prahu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Vrací hodnotu prahu. Pouze pro čtení float.

**Vrací:**
float