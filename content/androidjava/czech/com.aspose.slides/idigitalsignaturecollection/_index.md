---
title: IDigitalSignatureCollection
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Reprezentuje kolekci digitálních podpisů připojených k dokumentu.
type: docs
url: /cs/com.aspose.slides/idigitalsignaturecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Reprezentuje kolekci digitálních podpisů připojených k dokumentu.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací podpis podle indexu. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Přidá podpis na konci kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní podpis na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny podpisy z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```


Vrací podpis podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```


Přidá podpis na konci kolekce.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Podpis k přidání. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní podpis na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index podpisu, který má být smazán. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny podpisy z kolekce.