---
title: MakeObject()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un oggetto nell'heap e restituisce un puntatore condiviso a esso.
type: docs
weight: 2887
url: /it/system/makeobject/
---
## System::MakeObject(Args\&&...) funzione

Crea un oggetto nell'heap e restituisce un puntatore condiviso a esso.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Classe da istanziare. |
| Args | Tipi degli argomenti del costruttore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | Args\&&... | Argomenti del costruttore. |

### Valore di ritorno

[SmartPtr](../smartptr/) a un nuovo oggetto, sempre in modalità condivisa.

## System::MakeObject(Args\&&...) funzione

Crea un oggetto nell'heap e restituisce un puntatore condiviso a esso.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [SmartPtr](../smartptr/) a classe da istanziare. |
| Args | Tipi degli argomenti del costruttore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | Args\&&... | Argomenti del costruttore. |

### Valore di ritorno

[SmartPtr](../smartptr/) a un nuovo oggetto, sempre in modalità condivisa.

## Vedi anche

* Classe [SmartPtr](../smartptr/)
* Struttura [IsSmartPtr](../issmartptr/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)