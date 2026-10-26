---
title: IDigitalSignatureCollection
second_title: Aspose.Slides Androidhoz Java API referencia
description: A dokumentumhoz csatolt digitális aláírások gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/idigitalsignaturecollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Digitális aláírások gyűjteményét képviseli, amelyek egy dokumentumhoz vannak csatolva.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az aláírást az index alapján. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Hozzáadja az aláírást a gyűjtemény végére. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az aláírást a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes aláírást a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Visszaadja az aláírást az index alapján.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


Hozzáadja az aláírást a gyűjtemény végére.

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

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Hozzáadandó aláírás. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja az aláírást a megadott indexnél.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az aláírás indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes aláírást a gyűjteményből.