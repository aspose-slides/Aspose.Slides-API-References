---
title: IDigitalSignatureCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de assinaturas digitais anexadas a um documento.
type: docs
url: /pt/com.aspose.slides/idigitalsignaturecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Representa uma coleção de assinaturas digitais anexadas a um documento.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the signature by index. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Adds the signature at the end of collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the signature at the specified index. |
| [clear()](#clear--) | Removes all signatures from collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Returns the signature by index.

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


Adds the signature at the end of collection.

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
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Signature to add. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the signature at the specified index.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Index of the signature that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all signatures from collection.