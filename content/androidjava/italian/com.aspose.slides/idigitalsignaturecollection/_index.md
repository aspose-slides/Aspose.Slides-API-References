---
title: IDigitalSignatureCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una collezione di firme digitali allegate a un documento.
type: docs
url: /it/com.aspose.slides/idigitalsignaturecollection/
---
**Tutte le Interfacce Implementate:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Rappresenta una collezione di firme digitali allegate a un documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la firma per indice. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Aggiunge la firma alla fine della collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la firma all'indice specificato. |
| [clear()](#clear--) | Rimuove tutte le firme dalla collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Restituisce la firma per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


Aggiunge la firma alla fine della collezione.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Firma da aggiungere. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove la firma all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della firma da eliminare. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutte le firme dalla collezione.