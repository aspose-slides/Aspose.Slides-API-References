---
title: IVbaProjectFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar projeto VBA via interface COM
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
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lê o projeto VBA a partir de um contêiner OLE. |
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


Lê projeto VBA a partir de um contêiner OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] | Dados Ole byte[] |

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Projeto VBA lido