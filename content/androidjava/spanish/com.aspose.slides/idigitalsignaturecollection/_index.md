---
title: IDigitalSignatureCollection
second_title: Aspose.Slides para Android mediante la Referencia de la API Java
description: Representa una colección de firmas digitales adjuntas a un documento.
type: docs
url: /es/com.aspose.slides/idigitalsignaturecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Representa una colección de firmas digitales adjuntas a un documento.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la firma por índice. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Añade la firma al final de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la firma en el índice especificado. |
| [clear()](#clear--) | Elimina todas las firmas de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Devuelve la firma por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


Añade la firma al final de la colección.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Firma a añadir. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Elimina la firma en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la firma que debe eliminarse. |

### clear() {#clear--}
```
public abstract void clear()
```


Elimina todas las firmas de la colección.