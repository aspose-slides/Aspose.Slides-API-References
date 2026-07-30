---
title: StaticCastArray()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue il casting degli elementi dell'array specificato a un tipo diverso. Sovrascrivi per i casi in cui From è un oggetto SmartPtr.
type: docs
weight: 2978
url: /it/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funzione

Effettua il cast degli elementi dell'array specificato a un tipo diverso. Sovrascrivi per i casi in cui From è [SmartPtr](../smartptr/) obj.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| To | Il tipo al quale castare gli elementi dell'array specificato |
| From | Il tipo degli elementi dell'array da cui effettuare il cast |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Puntatore condiviso all'array contenente gli elementi da castare |

### Valore restituito

Un puntatore a un nuovo array contenente elementi di tipo **To** equivalenti agli elementi di **from**

Obsoleto
:   Aggiunto per compatibilità retroattiva. Usa ExplicitCast invece.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) funzione

Effettua il cast degli elementi dell'array specificato a un tipo diverso. Sovrascrivi per i casi in cui From è Boxable e To è [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| To | Il tipo al quale castare gli elementi dell'array specificato |
| From | Il tipo degli elementi dell'array da cui effettuare il cast |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Puntatore condiviso all'array contenente gli elementi da castare |

### Valore restituito

Un puntatore a un nuovo array contenente elementi di tipo **To** equivalenti agli elementi di **from**

Obsoleto
:   Aggiunto per compatibilità retroattiva. Usa ExplicitCast invece.

## Vedi anche

* Typedef [SharedPtr](../sharedptr/)
* Classe [Array](../array/)
* Classe [Object](../object/)
* Struttura [IsSmartPtr](../issmartptr/)
* Struttura [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)