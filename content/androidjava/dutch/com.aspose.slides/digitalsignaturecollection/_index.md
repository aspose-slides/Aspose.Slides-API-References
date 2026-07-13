---
title: DigitalSignatureCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie digitale handtekeningen voor die aan een document zijn gekoppeld.
type: docs
url: /nl/com.aspose.slides/digitalsignaturecollection/
---
**Erfelijkheid:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Stelt een collectie digitale handtekeningen voor die aan een document zijn gekoppeld.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de handtekening op index. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Voegt de handtekening toe aan het einde van de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de handtekening op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle handtekeningen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [size()](#size--) | Retourneert het aantal elementen in de collectie. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


Retourneert de handtekening op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```


Voegt de handtekening toe aan het einde van de collectie.

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
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Handtekening om toe te voegen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert de handtekening op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de handtekening die verwijderd moet worden. |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle handtekeningen uit de collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Een java.util.Iterator voor de volledige collectie.
### size() {#size--}
```
public final int size()
```


Retourneert het aantal elementen in de collectie. Alleen-lezen int.

**Retourneert:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Beginindex in de doel-array. |