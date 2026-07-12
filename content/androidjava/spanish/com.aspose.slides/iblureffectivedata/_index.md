---
title: IBlurEffectiveData
second_title: Aspose.Slides para Android mediante la referencia API de Java
description: Objeto inmutable que representa un efecto de difuminado que se aplica a toda la forma, incluido su relleno.
type: docs
url: /es/com.aspose.slides/iblureffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Objeto inmutable que representa un efecto de difuminado que se aplica a toda la forma, incluida su relleno. Todos los canales de color, incluido el alfa, se ven afectados.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRadius()](#getRadius--) | Devuelve o establece el radio del desenfoque. |
| [getGrow()](#getGrow--) | Determina si los límites del objeto deben ampliarse como resultado del desenfoque. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Devuelve o establece el radio del desenfoque. Solo lectura double.

**Devuelve:**  
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina si los límites del objeto deben ampliarse como resultado del desenfoque. True indica que los límites se amplían mientras que false indica que no lo hacen. Solo lectura boolean.

**Devuelve:**  
boolean