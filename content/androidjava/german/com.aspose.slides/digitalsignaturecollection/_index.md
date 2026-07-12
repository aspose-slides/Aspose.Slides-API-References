---
title: DigitalSignatureCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung digitaler Signaturen dar, die an ein Dokument angehängt sind.
type: docs
url: /de/com.aspose.slides/digitalsignaturecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Stellt eine Sammlung digitaler Signaturen dar, die an ein Dokument angehängt sind.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Signatur nach Index zurück. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Fügt die Signatur am Ende der Sammlung hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Signatur am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Signaturen aus der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [size()](#size--) | Gibt die Anzahl der Elemente in der Sammlung zurück. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```


Gibt die Signatur nach Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
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
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Hinzuzufügende Signatur. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt die Signatur am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der Signatur, die gelöscht werden soll. |

### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Signaturen aus der Sammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Ein IGenericEnumerator, der verwendet werden kann, um durch die Sammlung zu iterieren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - Ein java.util.Iterator für die gesamte Sammlung.
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Elemente in der Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur lesbar boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt eine Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |