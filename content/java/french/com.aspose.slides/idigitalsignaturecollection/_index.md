---
title: IDigitalSignatureCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de signatures numériques attachées à un document.
type: docs
url: /fr/com.aspose.slides/idigitalsignaturecollection/
---
**Toutes les interfaces implémentées:**  
com.aspose.slides.IGenericCollection  
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Représente une collection de signatures numériques attachées à un document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie la signature à l'index. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Ajoute la signature à la fin de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime la signature à l'index spécifié. |
| [clear()](#clear--) | Supprime toutes les signatures de la collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Renvoie la signature à l'index.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**  
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)

### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Ajoute la signature à la fin de la collection.

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Signature à ajouter. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime la signature à l'index spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de la signature à supprimer. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les signatures de la collection.