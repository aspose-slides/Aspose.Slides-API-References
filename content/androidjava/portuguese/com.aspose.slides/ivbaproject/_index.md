---
title: IVbaProject
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa o projeto VBA com macros de apresentação.
type: docs
url: /pt/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Representa o projeto VBA com macros de apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Retorna o nome do projeto VBA. |
| [getModules()](#getModules--) | Retorna a lista de todos os módulos que estão contidos no projeto VBA. |
| [getReferences()](#getReferences--) | Retorna a lista de todas as referências que estão contidas no projeto VBA. |
| [toBinary()](#toBinary--) | Retorna a representação binária do projeto VBA como contêiner OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto. |
### getName() {#getName--}
```
public abstract String getName()
```

Retorna o nome do projeto VBA. Somente leitura String.

**Retorna:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Retorna a lista de todos os módulos que estão contidos no projeto VBA. Somente leitura [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Retorna:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Retorna a lista de todas as referências que estão contidas no projeto VBA. Somente leitura [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Retorna:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Retorna a representação binária do projeto VBA como contêiner OLE. Somente leitura byte[].

**Retorna:**
byte[] - Representação binária do projeto VBA como contêiner OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Indica se o VBAProject está protegido por senha para visualizar as propriedades do projeto. Somente leitura boolean.

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