---
title: VbaProjectFactory
second_title: Aspose.Slides para Android via Referência da API Java
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
| [getInstance()](#getInstance--) | Instância estática da fábrica de projetos VBA. |
| [createVbaProject()](#createVbaProject--) | Cria um novo projeto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lê o projeto VBA do contêiner OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Instância estática da fábrica de projetos VBA. Somente leitura [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Retorna:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Cria um novo projeto VBA.

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Novo projeto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Lê o projeto VBA do contêiner OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] |  |

**Retorna:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Ler projeto VBA