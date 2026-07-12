---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Informações sobre o arquivo de apresentação
type: docs
url: /pt/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informações sobre o arquivo de apresentação
## Métodos

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Obtém True se a apresentação vinculada estiver criptografada, caso contrário False. |
| [isPasswordProtected()](#isPasswordProtected--) | Obtém um valor que indica se a apresentação vinculada está protegida por senha para abrir. |
| [isWriteProtected()](#isWriteProtected--) | Obtém um valor que indica se a apresentação vinculada está protegida contra gravação. |
| [getLoadFormat()](#getLoadFormat--) | Obtém o formato da apresentação vinculada. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Verifica se uma senha está correta para uma apresentação protegida com senha de abertura. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtém as propriedades do documento da apresentação vinculada. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Atualiza as propriedades da apresentação vinculada. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Grava a apresentação vinculada em um stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Grava a apresentação vinculada em um arquivo. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Obtém True se a apresentação vinculada estiver criptografada, caso contrário False. Somente leitura boolean.

**Retorna:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Obtém um valor que indica se a apresentação vinculada está protegida por senha para abrir.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Retorna:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


Obtém um valor que indica se a apresentação vinculada está protegida contra gravação.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Se a apresentação estiver protegida por senha para abrir, o valor da propriedade é igual a NotDefined. Veja a enumeração [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Obtém o formato da apresentação vinculada. Somente leitura [LoadFormat](../../com.aspose.slides/loadformat).

**Retorna:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


Verifica se uma senha está correta para uma apresentação protegida com senha de abertura.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha a ser verificada.

--------------------

Quando a senha for nula ou vazia, este método retorna false. |

**Retorna:**
boolean - True se a apresentação estiver protegida com senha de abertura e a senha estiver correta e false caso contrário.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Verifica se a senha para modificar está correta para uma apresentação protegida contra gravação.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha a ser verificada.

--------------------

1. Você deve verificar a propriedade (\#isWriteProtected.isWriteProtected) antes de chamar este método. 2. Quando a senha for nula ou vazia, este método retorna false. |

**Retorna:**
boolean - True se a apresentação estiver protegida contra gravação e a senha estiver correta. False caso contrário.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


Obtém as propriedades do documento da apresentação vinculada.

**Retorna:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - propriedades do documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


Atualiza as propriedades da apresentação vinculada.

--------------------

> ```
> Este exemplo mostra como chamar o método #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) para
>  atualizar as propriedades do documento retornadas pela chamada do método #readDocumentProperties.readDocumentProperties.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | propriedades do documento [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


Grava a apresentação vinculada em um stream.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.OutputStream | O stream deve ser posicionável e gravável. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


Grava a apresentação vinculada em um arquivo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| file | java.lang.String | Arquivo de apresentação. |