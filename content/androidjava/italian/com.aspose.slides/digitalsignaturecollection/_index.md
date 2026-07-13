---
title: DigitalSignatureCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di firme digitali collegate a un documento.
type: docs
url: /it/com.aspose.slides/digitalsignaturecollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
```
public class DigitalSignatureCollection extends DomObject<Presentation> implements IDigitalSignatureCollection
```

Rappresenta una raccolta di firme digitali collegate a un documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la firma per indice. |
| [add(IDigitalSignature signature)](#add-com.aspose.slides.IDigitalSignature-) | Aggiunge la firma alla fine della raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la firma all'indice specificato. |
| [clear()](#clear--) | Rimuove tutte le firme dalla raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera raccolta. |
| [size()](#size--) | Restituisce il numero di elementi nella raccolta. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
### get_Item(int index) {#get-Item-int-}
```
public final IDigitalSignature get_Item(int index)
```

Restituisce la firma per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature signature) {#add-com.aspose.slides.IDigitalSignature-}
```
public final void add(IDigitalSignature signature)
```

Aggiunge la firma alla fine della raccolta.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Firma da aggiungere. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove la firma all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della firma da eliminare. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutte le firme dalla raccolta.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDigitalSignature> iteratorJava()
```

Restituisce un iterator java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDigitalSignature> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi nella raccolta. Solo lettura int.

**Restituisce:**
int
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |