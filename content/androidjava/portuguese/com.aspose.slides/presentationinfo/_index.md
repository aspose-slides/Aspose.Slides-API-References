---
title: PresentationInfo
second_title: Aspose.Slides para Android via Referência da API Java
description: Informações sobre o arquivo de apresentação
type: docs
url: /pt/com.aspose.slides/presentationinfo/
---
**Herança:**  
java.lang.Object  

**Todas as Interfaces Implementadas:**  
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)  
```
public final class PresentationInfo implements IPresentationInfo
```  

Informações sobre o arquivo de apresentação  
## Métodos

| Método | Descrição |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Obtém True se a apresentação vinculada estiver criptografada, caso contrário False. |
| [isPasswordProtected()](#isPasswordProtected--) | Obtém um valor que indica se a apresentação vinculada está protegida por uma senha para abrir. |
| [isWriteProtected()](#isWriteProtected--) | Obtém um valor que indica se a apresentação vinculada está protegida contra gravação. |
| [getLoadFormat()](#getLoadFormat--) | Obtém o formato da apresentação vinculada. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Verifica se uma senha está correta para uma apresentação protegida com senha de abertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtém as propriedades do documento da apresentação vinculada. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Atualiza as propriedades da apresentação vinculada. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | grava a apresentação vinculada em um fluxo. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | grava a apresentação vinculada em um arquivo. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Obtém True se a apresentação vinculada estiver criptografada, caso contrário False. Booleano somente leitura.

**Retorna:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Obtém um valor que indica se a apresentação vinculada está protegida por uma senha para abrir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Retorna:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Obtém um valor que indica se a apresentação vinculada está protegida contra gravação.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Se a apresentação estiver protegida por uma senha para abrir, o valor da propriedade é igual a NotDefined.

**Retorna:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Obtém o formato da apresentação vinculada. Booleano somente leitura [LoadFormat](../../com.aspose.slides/loadformat).

**Retorna:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Verifica se uma senha está correta para uma apresentação protegida com senha de abertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha a ser verificada. |

--------------------

Quando a senha é nula ou vazia, este método retorna false. |

**Retorna:**  
boolean - True se a apresentação estiver protegida com senha de abertura e a senha estiver correta e false caso contrário.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha a ser verificada. |

--------------------

1. Você deve verificar a propriedade (\#isWriteProtected.isWriteProtected) antes de chamar este método. 2. Quando a senha for nula ou vazia, este método retorna false. |

**Retorna:**  
boolean - True se a apresentação estiver protegida contra gravação e a senha estiver correta. False caso contrário.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Obtém as propriedades do documento da apresentação vinculada.

**Retorna:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Atualiza as propriedades da apresentação vinculada.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Grava a apresentação vinculada em um fluxo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | O fluxo deve ser posicionável e gravável. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Grava a apresentação vinculada em um arquivo.

**Parâmetros:**  
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo da apresentação. |