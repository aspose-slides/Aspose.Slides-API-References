---
title: IDigitalSignatureCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av digitala signaturer som är bifogade till ett dokument.
type: docs
url: /sv/com.aspose.slides/idigitalsignaturecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Representerar en samling av digitala signaturer som är bifogade till ett dokument.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar signaturen efter index. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Lägger till signaturen i slutet av samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort signaturen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla signaturer från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Returnerar signaturen efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


Lägger till signaturen i slutet av samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Signatur att lägga till. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort signaturen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för signaturen som ska tas bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla signaturer från samlingen.