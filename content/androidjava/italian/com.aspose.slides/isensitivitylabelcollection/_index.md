---
title: ISensitivityLabelCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di etichette di sensibilità applicate al documento.
type: docs
url: /it/com.aspose.slides/isensitivitylabelcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
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
| [getCount()](#getCount--) | Ottiene il numero di tutti gli elementi nella raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Restituisce l'etichetta di sensibilità per indice. Sola lettura [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Aggiunge l'etichetta di sensibilità alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | java.lang.String | L'id dell'etichetta di sensibilità. |
| siteId | java.util.UUID | L'identificatore del sito Azure Active Directory (Azure AD). |
| isEnabled | boolean | Flag che indica se l'etichetta di sensibilità è abilitata. |
| methodType | int | Il metodo di assegnazione per l'etichetta di sensibilità. |

**Restituisce:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
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
public abstract void removeAt(int index)
```

Rimuove l'etichetta di sensibilità all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'etichetta di sensibilità da eliminare. |
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli elementi dalla raccolta.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ottiene il numero di tutti gli elementi nella raccolta. Sola lettura  int .

**Restituisce:**
int