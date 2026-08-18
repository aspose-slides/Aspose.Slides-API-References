---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides dla dokumentacji API Java
description: Nieodmienny obiekt, który reprezentuje efekt Alpha Bi-Level.
type: docs
url: /pl/com.aspose.slides/ialphabileveleffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Nieodmienny obiekt reprezentujący efekt Alpha Bi-Level. Wartości Alpha (Opacity) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste) i wartości Alpha większe lub równe progowi są zmieniane na 100% (całkowicie nieprzezroczyste).
## Metody

| Metoda | Opis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Zwraca próg efektu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Zwraca próg efektu. Float tylko do odczytu.

**Zwraca:**
float