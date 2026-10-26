---
title: SensitivityLabelCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di etichette di sensibilità applicate al documento.
type: docs
url: /it/com.aspose.slides/sensitivitylabelcollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Rappresenta una raccolta di etichette di sensibilità applicate al documento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'etichetta di sensibilità per indice. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Aggiunge l'etichetta di sensibilità alla fine della raccolta. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Aggiunge una SensitivityLabel alla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'etichetta di sensibilità all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [getCount()](#getCount--) | Restituisce il numero di elementi nella raccolta. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copia tutti gli elementi della raccolta nell'array specificato. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Restituisce l'etichetta di sensibilità per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Aggiunge l'etichetta di sensibilità alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | java.lang.String | L'ID dell'etichetta di sensibilità. |
| siteId | java.util.UUID | L'identificatore del sito Azure Active Directory (Azure AD). |
| isEnabled | boolean | Flag che indica se l'etichetta di sensibilità è abilitata. |
| methodType | int | Il metodo di assegnazione per l'etichetta di sensibilità. |

**Restituisce:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Aggiunge una SensitivityLabel alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | L'oggetto SensitivityLabel da aggiungere alla fine della raccolta. |

**Restituisce:**
int - L'indice al quale è stata aggiunta la SensitivityLabel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'etichetta di sensibilità all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'etichetta di sensibilità da eliminare. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli elementi dalla raccolta.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Un System.Collections.Generic.IEnumerator1 che può essere usato per iterare attraverso la raccolta.
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di elementi nella raccolta. Sola lettura  int .

**Restituisce:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Copia tutti gli elementi della raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |