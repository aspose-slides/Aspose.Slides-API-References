---
title: DigitalSignature
second_title: Referência da API Java do Aspose.Slides para Android
description: Assinatura digital em arquivo assinado.
type: docs
url: /pt/com.aspose.slides/digitalsignature/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Assinatura digital em arquivo assinado.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Inicializar instância de Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Criar objeto DigitalSignature com arquivo PFX e senha PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Comentar nova assinatura digital
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Adicionar assinatura digital à apresentação
>      pres.getDigitalSignatures().add(signature);
>      // Salvar apresentação
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Inicializar instância de Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Verificar se todas as assinaturas digitais são válidas
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Cria um novo objeto DigitalSignature com o certificado especificado. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Cria um novo objeto DigitalSignature com o caminho do arquivo de certificado especificado e a senha. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getCertificate()](#getCertificate--) | Objeto Certificate que foi usado para assinar o documento. |
| [isValid()](#isValid--) | Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. |
| [getSignTime()](#getSignTime--) | O momento em que o documento foi assinado. |
| [getComments()](#getComments--) | O propósito da assinatura. |
| [setComments(String value)](#setComments-java.lang.String-) | O propósito da assinatura. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Cria um novo objeto DigitalSignature com o certificado especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| certData | byte[] | um array de bytes contendo o certificado |
| password | java.lang.String | Senha necessária para acessar o certificado. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Cria um novo objeto DigitalSignature com o caminho do arquivo de certificado especificado e a senha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filePath | java.lang.String | Caminho para o arquivo com o certificado. |
| password | java.lang.String | Senha necessária para acessar o certificado. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Objeto Certificate que foi usado para assinar o documento. Somente leitura byte[].

**Retorna:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Se esta assinatura digital for válida e o documento não tiver sido adulterado, este valor será verdadeiro. Somente leitura boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

O momento em que o documento foi assinado. Somente leitura java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

O propósito da assinatura. Leitura/escrita String.

**Retorna:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

O propósito da assinatura. Leitura/escrita String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |