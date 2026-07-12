---
title: ILicense
second_title: Aspose.Slides para Android via Java API Reference
description: Fornece métodos para licenciar o componente.
type: docs
url: /pt/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Fornece métodos para licenciar o componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licencia o componente. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licencia o componente. |
| [resetLicense()](#resetLicense--) | Redefinir a licença |
| [isLicensed()](#isLicensed--) | Verifica se a licença foi aplicada ao componente |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Licencia o componente.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| licenseName | java.lang.String | Pode ser um nome de arquivo completo ou curto ou o nome de um recurso incorporado. Use uma string vazia para mudar para o modo de avaliação.

--------------------

Tenta encontrar a licença nos seguintes locais:

1. Caminho explícito.
2. A pasta da assembly do componente.
3. A pasta da assembly chamadora do cliente.
4. A pasta da assembly de entrada.
5. Um recurso incorporado na assembly chamadora do cliente. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Licencia o componente.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Um fluxo que contém a licença.

--------------------

Use este método para carregar uma licença a partir de um fluxo.

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

Redefinir a licença

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Use este método para redefinir a licença no componente

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```

Verifica se a licença foi aplicada ao componente

**Retorna:**
boolean - true se o componente estiver licenciado, caso contrário false