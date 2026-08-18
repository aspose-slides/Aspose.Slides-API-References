---
title: ProtectionManager
second_title: Referência da API Aspose.Slides para Java
description: Gerenciamento de proteção por senha da apresentação.
type: docs
url: /pt/com.aspose.slides/protectionmanager/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Gerenciamento de proteção por senha da Presentation.
## Métodos

| Método | Descrição |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Esta propriedade faz sentido, se a apresentação estiver protegida por senha. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Esta propriedade faz sentido, se a apresentação estiver protegida por senha. |
| [isEncrypted()](#isEncrypted--) | Obtém um valor que indica se esta instância está criptografada. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas. |
| [isWriteProtected()](#isWriteProtected--) | Obtém um valor que indica se esta apresentação está protegida contra gravação. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Criptografa a Presentation com a senha especificada. |
| [removeEncryption()](#removeEncryption--) | Remove a criptografia. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Define proteção contra gravação para esta apresentação com a senha especificada. |
| [removeWriteProtection()](#removeWriteProtection--) | Remove a proteção contra gravação desta apresentação. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Determina se uma apresentação está protegida por senha para modificação. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Obtém a senha usada para criptografar a apresentação. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtém ou define a recomendação de somente leitura. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtém ou define a recomendação de somente leitura. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Esta propriedade faz sentido, se a apresentação estiver protegida por senha. Se true então as propriedades do documento são criptografadas no arquivo de apresentação. Se false então as propriedades do documento são públicas enquanto a apresentação está criptografada. Boolean de leitura/gravação.

**Retorna:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Esta propriedade faz sentido, se a apresentação estiver protegida por senha. Se true então as propriedades do documento são criptografadas no arquivo de apresentação. Se false então as propriedades do documento são públicas enquanto a apresentação está criptografada. Boolean de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Obtém um valor que indica se esta instância está criptografada. Boolean de somente leitura.

Valor: true se a apresentação foi carregada a partir de um arquivo criptografado ou \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Retorna:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Esta propriedade faz sentido, se o arquivo de apresentação estiver protegido por senha e as propriedades do documento deste arquivo forem públicas. Valor true significa que apenas as propriedades do documento são carregadas de um arquivo de apresentação criptografado sem o uso de senha. Valor false significa que toda a apresentação criptografada é carregada com o uso da senha correta, não apenas as propriedades do documento são carregadas. Se a apresentação não estiver criptografada, então o valor da propriedade é sempre false. Se as propriedades do documento de um arquivo criptografado não forem públicas, então o valor da propriedade é sempre false. Se Presentation.EncryptDocumentProperties for true, então o valor da propriedade IsOnlyDocumentPropertiesLoaded é sempre false. Boolean de somente leitura.

**Retorna:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Obtém um valor que indica se esta apresentação está protegida contra gravação. Boolean de somente leitura.

**Retorna:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Criptografa a Presentation com a senha especificada.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encryptionPassword | java.lang.String | A senha. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Remove a criptografia.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Define proteção contra gravação para esta apresentação com a senha especificada.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Remove a proteção contra gravação desta apresentação.

--------------------

> ```
> Este código de exemplo mostra como remover a proteção contra gravação de uma apresentação PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| password | java.lang.String | A senha para verificação.

1. Você deve verificar a propriedade (\#isWriteProtected.isWriteProtected) antes de chamar este método. 2. Quando a senha é nula ou vazia, este método retorna false. |

**Retorna:**
boolean - True se a senha for válida; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Obtém a senha que é usada para criptografar a apresentação. String de somente leitura.

**Retorna:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Obtém ou define a recomendação de somente leitura. Boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Obtém ou define a recomendação de somente leitura. Boolean de leitura/gravação.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |