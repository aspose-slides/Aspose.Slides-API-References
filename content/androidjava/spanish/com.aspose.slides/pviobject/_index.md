---
title: PVIObject
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Encapsula la infraestructura básica de servicio para objetos que pueden ser sujetos de herencia de valores de propiedad.
type: docs
url: /es/com.aspose.slides/pviobject/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Encapsula la infraestructura básica de servicio para objetos que pueden ser sujetos de herencia de valores de propiedad.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compara con el objeto especificado. |
| [hashCode()](#hashCode--) | Devuelve el código hash. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Solo lectura long.

**Devuelve:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Devuelve el padre IPresentationComponent. Solo lectura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Devuelve:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```



**Devuelve:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Devuelve la presentación. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compara con el objeto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a comparar. |

**Devuelve:**
boolean - True si los objetos son iguales, de lo contrario false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Devuelve el código hash.

**Devuelve:**
int - Código hash.