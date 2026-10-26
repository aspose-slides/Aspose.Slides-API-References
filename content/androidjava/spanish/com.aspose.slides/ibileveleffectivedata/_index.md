---
title: IBiLevelEffectiveData
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Objeto inmutable que representa un efecto Bi-Level (blanco/negro).
type: docs
url: /es/com.aspose.slides/ibileveleffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el valor de umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen en blanco. Los valores de efecto alfa no se ven afectados por este efecto.
## Métodos

| Método | Descripción |
| --- | --- |
| [getThreshold()](#getThreshold--) | Devuelve el valor del umbral. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Devuelve el valor del umbral. Float de solo lectura.

**Devuelve:**
float