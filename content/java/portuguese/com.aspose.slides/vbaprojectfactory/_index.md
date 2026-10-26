---
title: VbaProjectFactory
second_title: Referência da API Aspose.Slides para Java
description: Permite criar projeto VBA via interface COM
type: docs
url: /pt/com.aspose.slides/vbaprojectfactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Permite criar projeto VBA via interface COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory static instance. |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


VBA project factory static instance. Somente leitura [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Retorna:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Creates new VBA project.

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Novo projeto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Reads VBA project from OLE container.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] |  |

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Lê o projeto VBA