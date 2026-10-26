---
title: IDigitalSignatureCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję podpisów cyfrowych dołączonych do dokumentu.
type: docs
url: /pl/com.aspose.slides/idigitalsignaturecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Reprezentuje kolekcję podpisów cyfrowych dołączonych do dokumentu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca podpis według indeksu. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Dodaje podpis na końcu kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa podpis o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie podpisy z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Zwraca podpis według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Dodaje podpis na końcu kolekcji.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Podpis do dodania. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa podpis o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks podpisu, który ma zostać usunięty. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie podpisy z kolekcji.