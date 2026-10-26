---
title: MasterSlideCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di diapositive master.
type: docs
url: /it/com.aspose.slides/masterslidecollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Rappresenta una raccolta di diapositive master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Rimuove le diapositive master inutilizzate. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Aggiunge una copia di una diapositiva master specificata alla fine della raccolta. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
### size() {#size--}
```
public final int size()
```


Ottiene il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Solo lettura [MasterSlide](../../com.aspose.slides/masterslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```


Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositiva master da rimuovere dalla raccolta. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da rimuovere.

--------------------

Per evitare il lancio di PptxEditException, verificare la proprietà HasDependingSlides del master prima. |
### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```


Rimuove le diapositive master inutilizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina se questo metodo deve rimuovere master inutilizzati anche se la sua proprietà [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) è impostata su true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```


Aggiunge una copia di una diapositiva master specificata alla fine della raccolta. Le diapositive di layout collegate verranno copiate anch'esse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva da clonare. |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva aggiunta.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. Le diapositive di layout collegate verranno copiate anch'esse.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Istituziona la classe Presentation per caricare il file della presentazione di origine
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Istituziona la classe Presentation per la presentazione di destinazione (dove la diapositiva sarà clonata)
>      Presentation destPres = new Presentation();
>      try {
>          // Istituziona ISlide dalla raccolta di diapositive nella presentazione di origine insieme a
>          // Diapositiva master
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Ottieni le diapositive master della presentazione di destinazione
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clona la diapositiva master desiderata dalla presentazione di origine alla raccolta dei master nella
>          // Presentazione di destinazione
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Raccolta di diapositive nella presentazione di destinazione
>          ISlideCollection slds = destPres.getSlides();
>          // Clona la diapositiva di origine nella raccolta di diapositive di destinazione.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Salva la presentazione di destinazione su disco
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva da clonare. |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva master inserita.
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.