---
title: IMasterSlideCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di diapositive master.
type: docs
url: /it/com.aspose.slides/imasterslidecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Rappresenta una raccolta di diapositive master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Rimuove le diapositive master inutilizzate. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Aggiunge una copia di una diapositiva master specificata alla fine della raccolta. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Solo lettura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositiva master da rimuovere dalla raccolta. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Rimuove le diapositive master inutilizzate.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina se questo metodo deve rimuovere master inutilizzati anche se le sue proprietà [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) sono impostate su true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Aggiunge una copia di una diapositiva master specificata alla fine della raccolta. Le diapositive di layout collegate saranno copiate anch'esse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva da clonare. |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva aggiunta.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. Le diapositive di layout collegate saranno copiate anch'esse.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva da clonare. |

**Restituisce:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva master inserita.