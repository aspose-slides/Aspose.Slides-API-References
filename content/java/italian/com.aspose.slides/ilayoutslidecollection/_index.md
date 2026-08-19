---
title: ILayoutSlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una classe base per la collezione di diapositive di layout.
type: docs
url: /it/com.aspose.slides/ilayoutslidecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Rappresenta una classe base per la collezione di diapositive di layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la diapositiva di layout per indice. |
| [getByType(byte type)](#getByType-byte-) | Restituisce la prima diapositiva di layout del tipo specificato. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Rimuove un layout dalla collezione. |
| [removeUnused()](#removeUnused--) | Rimuove le diapositive di layout non utilizzate (diapositive di layout il cui HasDependingSlides è false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Restituisce la diapositiva di layout per indice. Solo lettura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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


Restituisce la prima diapositiva di layout del tipo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | byte | Un tipo di diapositiva di layout da trovare. |

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
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositiva di layout da rimuovere dalla collezione.

--------------------

1) Per evitare il lancio di PptxEditException controllare prima la proprietà HasDependingSlides del layout. 2) È anche possibile utilizzare il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Rimuove le diapositive di layout non utilizzate (diapositive di layout il cui HasDependingSlides è false).