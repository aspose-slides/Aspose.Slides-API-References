---
title: IProtectionManager
second_title: Aspose.Slides for Android via Referência de API Java
description: Gerenciamento de proteção por senha de apresentações.
type: docs
url: /pt/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Gerenciamento de proteção por senha de apresentações.
## Métodos

| Method | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Esta propriedade faz sentido, se a apresentação estiver protegida por senha. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Esta propriedade faz sentido, se a apresentação estiver protegida por senha. |
| [isEncrypted()](#isEncrypted--) | Obtém um valor que indica se esta instância está criptografada. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas. |
| [isWriteProtected()](#isWriteProtected--) | Obtém um valor que indica se esta apresentação está protegida contra gravação. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Retorna a senha de criptografia. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtém ou define a recomendação de somente leitura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtém ou define a recomendação de somente leitura. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Criptografa a apresentação com a senha especificada. |
| [removeEncryption()](#removeEncryption--) | Remove a criptografia. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Define proteção contra gravação para esta apresentação com a senha especificada. |
| [removeWriteProtection()](#removeWriteProtection--) | Remove a proteção contra gravação para esta apresentação. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina se uma apresentação está protegida por senha para modificação. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Esta propriedade faz sentido, se a apresentação estiver protegida por senha. Se for true então as propriedades do documento são criptografadas no arquivo da apresentação. Se for false então as propriedades do documento são públicas enquanto a apresentação está criptografada. Boolean de leitura/gravação.

**Retorna:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Esta propriedade faz sentido, se a apresentação estiver protegida por senha. Se for true então as propriedades do documento são criptografadas no arquivo da apresentação. Se for false então as propriedades do documento são públicas enquanto a apresentação está criptografada. Boolean de leitura/gravação.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Obtém um valor que indica se esta instância está criptografada. Boolean somente leitura.

Valor: true se a apresentação foi carregada a partir de um arquivo criptografado ou \#encrypt(String).encrypt(String) foi chamado; caso contrário, false.

**Retorna:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas. Valor true significa que apenas as propriedades do documento foram carregadas de um arquivo de apresentação criptografado sem uso de senha. Valor false significa que a apresentação inteira criptografada foi carregada com a senha correta, não apenas as propriedades do documento. Se a apresentação não estiver criptografada, o valor da propriedade é sempre false. Se as propriedades do documento de um arquivo criptografado não forem públicas, o valor da propriedade é sempre false. Se PresentationEx.EncryptDocumentProperties for true, então o valor da propriedade IsOnlyDocumentPropertiesLoaded é sempre false. Boolean somente leitura.

**Retorna:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Obtém um valor que indica se esta apresentação está protegida contra gravação. Boolean somente leitura.

**Retorna:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Retorna a senha de criptografia. String somente leitura.

**Retorna:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Obtém ou define a recomendação de somente leitura. Boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Retorna:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Obtém ou define a recomendação de somente leitura. Boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Criptografa a apresentação com a senha especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | A senha. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Remove a criptografia.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Define proteção contra gravação para esta apresentação com a senha especificada.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | A senha. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Remove a proteção contra gravação desta apresentação.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Determina se uma apresentação está protegida por senha para modificação.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | A senha para verificação.

--------------------

1. Você deve verificar a propriedade (\#isWriteProtected.isWriteProtected) antes de chamar este método. 2. Quando a senha for nula ou vazia, este método retorna false. |

**Retorna:**
boolean - Verdadeiro se a senha for válida; caso contrário, false.