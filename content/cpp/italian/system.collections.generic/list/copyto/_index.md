---
title: CopyTo()
second_title: Riferimento API Aspose.Slides per C++
description: Copia gli elementi della lista negli elementi dell'array esistente.
type: docs
weight: 209
url: /it/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metodo

Copia gli elementi dell'elenco negli elementi dell'array esistente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Array di destinazione. |
| arrayIndex | int | Indice iniziale dell'array di destinazione. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metodo

Copia tutti gli elementi negli elementi dell'array esistente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) per copiare gli elementi dentro. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metodo

Copia gli elementi a partire dall'indice specificato negli elementi dell'array esistente.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Un indice basato su zero dell'elemento nell'elenco rappresentato dall'oggetto corrente da cui iniziare la copia |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) per copiare gli elementi dentro. |
| arrayIndex | int | Posizione iniziale nell'array di destinazione. |
| count | int | Numero di elementi da copiare. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)