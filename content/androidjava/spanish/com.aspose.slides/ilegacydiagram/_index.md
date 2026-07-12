---
title: ILegacyDiagram
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un objeto de diagrama heredado
type: docs
url: /es/com.aspose.slides/ilegacydiagram/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Representa un objeto de diagrama heredado
## Métodos

| Método | Descripción |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Convierte el diagrama heredado en un objeto SmartArt editable. |
| [convertToGroupShape()](#convertToGroupShape--) | Convierte el diagrama heredado en una forma de grupo editable. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```


Convierte el diagrama heredado en un objeto SmartArt editable. El objeto SmartArt creado se agrega a la forma de grupo padre en la misma posición.

**Devuelve:**
[ISmartArt](../../com.aspose.slides/ismartart) - Objeto SmartArt creado.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```


Convierte el diagrama heredado en una forma de grupo editable. El objeto GroupShape creado se agrega a la forma de grupo padre en la misma posición.

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objeto GroupShape creado.