---
title: IBackgroundEffectiveData
second_title: Aspose.Slides para Android vía referencia de API Java
description: Objeto inmutable que contiene propiedades de fondo efectivas.
type: docs
url: /es/com.aspose.slides/ibackgroundeffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

Objeto inmutable que contiene propiedades de fondo efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [IBackground](../../com.aspose.slides/ibackground) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Devuelve el formato de relleno efectivo. |
| [getEffectFormat()](#getEffectFormat--) | Devuelve el formato de efecto efectivo. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


Devuelve el formato de relleno efectivo. Solo lectura [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**Devuelve:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


Devuelve el formato de efecto efectivo. Solo lectura [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**Devuelve:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)