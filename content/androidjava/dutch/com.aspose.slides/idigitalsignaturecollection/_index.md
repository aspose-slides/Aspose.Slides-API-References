---
title: IDigitalSignatureCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling digitale handtekeningen voor die aan een document zijn gekoppeld.
type: docs
url: /nl/com.aspose.slides/idigitalsignaturecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Stelt een verzameling digitale handtekeningen voor die aan een document zijn gekoppeld.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de handtekening op index. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Voegt de handtekening toe aan het einde van de verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de handtekening op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle handtekeningen uit de verzameling. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Retourneert de handtekening op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Voegt de handtekening toe aan het einde van de verzameling.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Handtekening om toe te voegen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de handtekening op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de handtekening die verwijderd moet worden. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle handtekeningen uit de verzameling.