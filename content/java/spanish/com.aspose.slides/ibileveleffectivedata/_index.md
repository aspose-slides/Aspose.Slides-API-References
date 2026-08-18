---
title: IBiLevelEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que representa un efecto Bi-Level negro/blanco.
type: docs
url: /es/com.aspose.slides/ibileveleffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto Bi-Level (black/white). Los colores de entrada cuya luminancia sea inferior al valor del umbral especificado se cambian a negro. Los colores de entrada cuya luminancia sea mayor o igual al valor especificado se establecen a blanco. Los valores de efecto alfa no se ven afectados por este efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getThreshold()](#getThreshold--) | Devuelve el valor del umbral. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Devuelve el valor del umbral. Solo lectura float.

**Devuelve:**
float