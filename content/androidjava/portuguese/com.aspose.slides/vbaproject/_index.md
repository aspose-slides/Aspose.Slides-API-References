---
title: VbaProject
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um projeto VBA com macros de apresentação.
type: docs
url: /pt/com.aspose.slides/vbaproject/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Representa um projeto VBA com macros de apresentação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [VbaProject()](#VbaProject--) | Este construtor cria um novo projeto VBA do zero. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Este construtor carrega o projeto VBA a partir da representação binária do contêiner OLE. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Retorna o nome do projeto VBA. |
| [getModules()](#getModules--) | Retorna a lista de todos os módulos que estão contidos no projeto VBA. |
| [getReferences()](#getReferences--) | Retorna a lista de todas as referências que estão contidas no projeto VBA. |
| [toBinary()](#toBinary--) | Retorna a representação binária do projeto VBA como contêiner OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Este construtor cria um novo projeto VBA do zero. O projeto será criado na 1252 Windows Latin 1 (ANSI) página de código

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Este construtor carrega o projeto VBA a partir da representação binária do contêiner OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Retorna o nome do projeto VBA. Somente leitura String.

**Retorna:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Retorna a lista de todos os módulos que estão contidos no projeto VBA. Somente leitura [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Retorna:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Retorna a lista de todas as referências que estão contidas no projeto VBA. Somente leitura [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Retorna:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Retorna a representação binária do projeto VBA como contêiner OLE

**Retorna:**
byte[] - Representação binária do projeto VBA como contêiner OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto. Somente leitura boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorna:**
boolean