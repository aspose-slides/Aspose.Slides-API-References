---
title: BlockCopy()
second_title: Riferimento API di Aspose.Slides per C++
description: Copia un numero specificato di byte dal buffer di origine al buffer di destinazione.
type: docs
weight: 1
url: /it/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) metodo


Copia un numero specificato di byte dal buffer di origine al buffer di destinazione.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const **uint8_t** * | Puntatore al buffer di origine |
| srcOffset | int | Un offset di byte nel buffer di origine in cui inizia la copia |
| dst | **uint8_t** * | Puntatore al buffer di destinazione |
| dstOffset | int | Un offset di byte nel buffer di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi dell'array di origine |
| TDst | Il tipo degli elementi dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | L'array di origine |
| srcOffset | int | Un offset di byte nel sorgente array in cui inizia la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | L'array di destinazione |
| dstOffset | int | Un offset di byte nell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) metodo


Interpreta due array specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | L'array di origine |
| srcOffset | int | Un offset di byte nel sorgente array in cui inizia la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | L'array di destinazione |
| dstOffset | int | Un offset di byte nell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi della vista dell'array di origine |
| TDst | Il tipo degli elementi della vista dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vista dell'array di origine |
| srcOffset | int | Un offset di byte nella vista dell'array di origine in cui inizia la copia |
| dst | const System::Details::ArrayView\<TDst\>\& | La vista dell'array di destinazione |
| dstOffset | int | Un offset di byte nella vista dell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi dell'array di origine |
| TDst | Il tipo degli elementi della vista dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | L'array di origine |
| srcOffset | int | Un offset di byte nell'array di origine in cui inizia la copia |
| dst | const System::Details::ArrayView\<TDst\>\& | La vista dell'array di destinazione |
| dstOffset | int | Un offset di byte nella vista dell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi della vista dell'array di origine |
| TDst | Il tipo degli elementi dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | La vista dell'array di origine |
| srcOffset | int | Un offset di byte nella vista dell'array di origine in cui inizia la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | L'array di destinazione |
| dstOffset | int | Un offset di byte nell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi dell'array di stack di origine |
| NS | La dimensione dell'array di stack di origine |
| TDst | Il tipo degli elementi dell'array di stack di destinazione |
| ND | La dimensione dell'array di stack di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | L'array di stack di origine |
| srcOffset | int | Un offset di byte nell'array di stack di origine in cui inizia la copia |
| dst | const System::Details::StackArray\<TDst, ND\>\& | L'array di stack di destinazione |
| dstOffset | int | Un offset di byte nell'array di stack di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi dell'array di origine |
| TDst | Il tipo degli elementi dell'array di stack di destinazione |
| ND | La dimensione dell'array di stack di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | L'array di origine |
| srcOffset | int | Un offset di byte nell'array di origine in cui inizia la copia |
| dst | const System::Details::StackArray\<TDst, ND\>\& | L'array di stack di destinazione |
| dstOffset | int | Un offset di byte nell'array di stack di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) metodo


Interpreta due array tipizzati specificati come array grezzi di byte e copia i dati da uno all'altro.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TSrc | Il tipo degli elementi dell'array di stack di origine |
| NS | La dimensione dell'array di stack di origine |
| TDst | Il tipo degli elementi dell'array di destinazione |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | L'array di stack di origine |
| srcOffset | int | Un offset di byte nell'array di stack di origine in cui inizia la copia |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | L'array di destinazione |
| dstOffset | int | Un offset di byte nell'array di destinazione in cui iniziare l'inserimento dei dati |
| count | int | Il numero di byte da copiare |

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [Buffer](../)
* Class [Array](../../array/)
* Class [ArrayBase](../../arraybase/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)