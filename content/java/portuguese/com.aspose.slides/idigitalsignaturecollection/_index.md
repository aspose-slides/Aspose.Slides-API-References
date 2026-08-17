---
title: IDigitalSignatureCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de assinaturas digitais anexadas a um documento.
type: docs
url: /pt/com.aspose.slides/idigitalsignaturecollection/
---
**Todas as interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Representa uma coleção de assinaturas digitais anexadas a um documento.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a assinatura por índice. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Adiciona a assinatura ao final da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a assinatura no índice especificado. |
| [clear()](#clear--) | Remove todas as assinaturas da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Retorna a assinatura por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Adiciona a assinatura ao final da coleção.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Assinatura a ser adicionada. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove a assinatura no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da assinatura que deve ser excluída. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as assinaturas da coleção.