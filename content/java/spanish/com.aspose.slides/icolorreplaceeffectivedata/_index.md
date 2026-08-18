---
title: IColorReplaceEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que representa un efecto de Reemplazo de Color.
type: docs
url: /es/com.aspose.slides/icolorreplaceeffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorReplaceEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto de Reemplazo de Color. Todos los colores del efecto se cambian a un color fijo. Los valores alfa no se ven afectados.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Devuelve el formato de color que reemplazará el color de cada píxel. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Devuelve el formato de color que reemplazará el color de cada píxel. Solo lectura java.awt.Color.

**Devuelve:**
java.awt.Color