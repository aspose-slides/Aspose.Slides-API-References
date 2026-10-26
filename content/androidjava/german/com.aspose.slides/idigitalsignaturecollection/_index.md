---
title: IDigitalSignatureCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung digitaler Signaturen dar, die einem Dokument beigefügt sind.
type: docs
url: /de/com.aspose.slides/idigitalsignaturecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Stellt eine Sammlung digitaler Signaturen dar, die einem Dokument beigefügt sind.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Signatur anhand des Index zurück. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Fügt die Signatur am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Signatur am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Signaturen aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Gibt die Signatur anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Fügt die Signatur am Ende der Sammlung hinzu.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Signatur, die hinzugefügt werden soll. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt die Signatur am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu löschenden Signatur. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Signaturen aus der Sammlung.