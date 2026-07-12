---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Objeto inmutable que representa un efecto Alpha Bi-Level.
type: docs
url: /es/com.aspose.slides/ialphabileveleffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto Alpha Bi-Level. Los valores Alpha (Opacity) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alpha mayores o iguales al umbral se cambian al 100 % (totalmente opaco).
## Métodos

| Método | Descripción |
| --- | --- |
| [getThreshold()](#getThreshold--) | Devuelve el umbral del efecto. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Devuelve el umbral del efecto. Float de solo lectura.

**Devuelve:**
float