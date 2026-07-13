---
title: ILayoutSlideCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una classe base per la raccolta di diapositive layout.
type: docs
url: /it/com.aspose.slides/ilayoutslidecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Rappresenta una classe base per la raccolta di diapositive layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la diapositiva layout per indice. |
| [getByType(byte type)](#getByType-byte-) | Restituisce la prima diapositiva layout del tipo specificato. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Rimuove un layout dalla collezione. |
| [removeUnused()](#removeUnused--) | Rimuove le diapositive layout inutilizzate (diapositive layout il cui HasDependingSlides è false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Restituisce la diapositiva layout per indice. Solo lettura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Restituisce la prima diapositiva layout del tipo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | byte | Un tipo di diapositiva layout da trovare. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) con il tipo specificato o null se non vengono trovati layout.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Rimuove un layout dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositiva layout da rimuovere dalla collezione.

--------------------

1) Per evitare il lancio di PptxEditException, controllare la proprietà HasDependingSlides del layout prima. 2) È possibile usare anche [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metodo per semplificare il codice. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Rimuove le diapositive layout inutilizzate (diapositive layout il cui HasDependingSlides è false).