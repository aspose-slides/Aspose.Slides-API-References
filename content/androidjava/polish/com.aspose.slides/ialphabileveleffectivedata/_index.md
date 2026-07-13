---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides dla Androida - dokumentacja API Java
description: Niezmienny obiekt reprezentujący efekt Alpha Bi-Level.
type: docs
url: /pl/com.aspose.slides/ialphabileveleffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Niezmienny obiekt reprezentujący efekt Alpha Bi-Level. Wartości Alpha (Opacity) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste).
## Metody

| Metoda | Opis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Zwraca próg efektu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Zwraca próg efektu. Tylko do odczytu float.

**Zwraca:**
float