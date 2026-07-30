---
title: Ref()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un riferimento all'oggetto DynamicWeakPtr. Utilizzato dal traduttore quando si passano argomenti di funzione per riferimento.
type: docs
weight: 2458
url: /it/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) function

Crea un riferimento all'oggetto [DynamicWeakPtr](../dynamicweakptr/). Utilizzato dal traduttore quando si passano argomenti di funzione per riferimento.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo dell'oggetto puntato. |
| trunkMode | Modalità del puntatore intelligente stesso. |
| weakLeafs | Indici degli argomenti del template per i quali deve essere chiamato il metodo SetTemplateWeakPtr. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Puntatore intelligente a cui creare riferimento. |

### Valore di ritorno

Riferimento al puntatore intelligente.

## System::Ref(T\&) function

Funzione di supporto per ottenere riferimenti a oggetti. Utilizzata per garantire che [System::DynamicWeakPtr](../dynamicweakptr/) aggiorni l'oggetto referenziato dopo le assegnazioni.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo a cui creare riferimento. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T\& | Valore a cui creare riferimento. |

### Valore di ritorno

Riferimento al valore passato a questa funzione.

## Vedi anche

* Classe [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)