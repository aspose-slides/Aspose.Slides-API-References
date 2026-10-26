---
title: ILegacyDiagram
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto de diagrama legado
type: docs
url: /pt/com.aspose.slides/ilegacydiagram/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

Representa um objeto de diagrama legado
## Métodos

| Método | Descrição |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converte diagrama legado em objeto SmartArt editável. |
| [convertToGroupShape()](#convertToGroupShape--) | Converte diagrama legado em group shape editável. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

Converte diagrama legado em objeto SmartArt editável. O objeto SmartArt criado é adicionado ao group shape pai na mesma posição.

**Retorna:**
[ISmartArt](../../com.aspose.slides/ismartart) - Objeto SmartArt criado.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

Converte diagrama legado em group shape editável. O objeto GroupShape criado é adicionado ao group shape pai na mesma posição.

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objeto GroupShape criado.