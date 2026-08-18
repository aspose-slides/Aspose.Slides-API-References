---
title: IDigitalSignatureCollection
second_title: Aspose.Slides Java API Referenciája
description: A dokumentumhoz csatolt digitális aláírások gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/idigitalsignaturecollection/
---
**Minden megvalósított interfész:**  
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

A dokumentumhoz csatolt digitális aláírások gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja az aláírást index szerint. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Hozzáadja az aláírást a gyűjtemény végéhez. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az aláírást a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes aláírást a gyűjteményből. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Visszaadja az aláírást index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Hozzáadja az aláírást a gyűjtemény végéhez.

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Hozzáadandó aláírás. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az aláírást a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az aláírás indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes aláírást a gyűjteményből.