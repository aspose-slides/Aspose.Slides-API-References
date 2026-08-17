---
title: LegacyDiagram
second_title: Referência da API Aspose.Slides para Java
description: Representa um objeto de diagrama legado.
type: docs
url: /pt/com.aspose.slides/legacydiagram/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILegacyDiagram](../../com.aspose.slides/ilegacydiagram)
```
public class LegacyDiagram extends GraphicalObject implements ILegacyDiagram
```

Representa um objeto de diagrama legado.
## Métodos

| Método | Descrição |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | Converte diagrama legado em um objeto SmartArt editável. |
| [convertToGroupShape()](#convertToGroupShape--) | Converte diagrama legado em um shape de grupo editável. |
### convertToSmartArt() {#convertToSmartArt--}
```
public final ISmartArt convertToSmartArt()
```


Converte diagrama legado em um objeto SmartArt editável. O objeto SmartArt criado é adicionado ao shape de grupo pai na mesma posição.

**Retorna:**
[ISmartArt](../../com.aspose.slides/ismartart) - Objeto SmartArt criado.
### convertToGroupShape() {#convertToGroupShape--}
```
public final IGroupShape convertToGroupShape()
```


Converte diagrama legado em um shape de grupo editável. O objeto GroupShape criado é adicionado ao shape de grupo pai na mesma posição.

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Objeto GroupShape criado.