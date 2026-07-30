---
title: Cast()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue il cast del puntatore al proprio tipo.
type: docs
weight: 287
url: /it/system/smartptr/cast/
---
## SmartPtr::Cast() const metodo


Casta il puntatore al suo stesso tipo.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di destinazione dell'oggetto puntato. |
| Check | Flag per lanciare un'eccezione se il cast non è disponibile. |

### Valore di ritorno

Puntatore del tipo modificato, sempre in modalità condivisa.

## SmartPtr::Cast() const metodo


Casta il puntatore al tipo base usando static_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di destinazione dell'oggetto puntato. |
| Check | Flag per lanciare un'eccezione se il cast non è disponibile. |

### Valore di ritorno

Puntatore del tipo modificato, sempre in modalità condivisa.

## SmartPtr::Cast() const metodo


Casta il puntatore al tipo derivato usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di destinazione dell'oggetto puntato. |
| Check | Flag per lanciare un'eccezione se il cast non è disponibile. |

### Valore di ritorno

Puntatore del tipo modificato, sempre in modalità condivisa. Lancia InvalidCastException se la conversione non è disponibile.

## SmartPtr::Cast() const metodo


Casta il puntatore al tipo derivato usando dynamic_cast.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Y | Tipo di destinazione dell'oggetto puntato. |
| Check | Flag per lanciare un'eccezione se il cast non è disponibile. |

### Valore di ritorno

Puntatore del tipo modificato, sempre in modalità condivisa. Restituisce nullptr se la conversione non è disponibile.

## Vedi anche

* Classe [SmartPtr](../)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)