---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /pt/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Permite criar projeto VBA via interface COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Cria um novo projeto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lê o projeto VBA do contêiner OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Cria um novo projeto VBA.

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Novo projeto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Lê o projeto VBA do contêiner OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados Ole byte[] |

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projeto VBA lido