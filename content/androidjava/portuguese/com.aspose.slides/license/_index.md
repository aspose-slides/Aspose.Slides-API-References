---
title: License
second_title: Aspose.Slides para Android via Java Referência da API
description: Fornece métodos para licenciar o componente.
type: docs
url: /pt/com.aspose.slides/license/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Fornece métodos para licenciar o componente.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [License()](#License--) | Inicializa uma nova instância desta classe. |
## Métodos

| Método | Descrição |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia o componente. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Licencia o componente. |
| [getVersion()](#getVersion--) | Retorna a versão do Aspose.Slides para Android via Java. |
| [resetLicense()](#resetLicense--) | Redefinir a licença. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Inicializa uma nova instância desta classe.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Licencia o componente.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Um fluxo que contém a licença. Use null para mudar para o modo de avaliação. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Licencia o componente.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| namePath | java.lang.String | Pode ser um nome de arquivo completo ou curto ou o nome de um recurso incorporado. Use uma string vazia para mudar para o modo de avaliação. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Retorna a versão do Aspose.Slides para Android via Java.

**Retorna:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Redefinir a licença. Use este método para redefinir a licença no componente.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Verifica se a licença está aplicada ao componente

**Retorna:**
boolean