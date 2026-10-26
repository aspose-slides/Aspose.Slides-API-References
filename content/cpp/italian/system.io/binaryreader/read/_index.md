---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge un singolo carattere dal flusso di input.
type: docs
weight: 66
url: /it/system.io/binaryreader/read/
---
## BinaryReader::Read() metodo


Legge un singolo carattere dal flusso di input.

```cpp
virtual int System::IO::BinaryReader::Read()
```


### Valore di ritorno

Carattere letto codificato in UTF-16; se il carattere letto è rappresentato da due codepoint nella codifica UTF-16, viene restituito solo il surrogato alto.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) metodo


Legge il numero specificato di byte dal flusso di input e li scrive nell'array di byte specificato.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte dove scrivere i byte letti |
| index | int | Una posizione basata su zero in **buffer** per iniziare la scrittura |
| count | int | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) metodo


Legge il numero specificato di caratteri dal flusso di input, li converte in codifica UTF-16 e scrive i caratteri UTF-16 risultanti nell'array di caratteri specificato a partire dalla posizione specificata.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | L'array di caratteri UTF-16 dove scrivere i caratteri letti dal flusso di input |
| index | int | Un indice basato su zero in **buffer** da cui iniziare la scrittura |
| count | int | Il numero di caratteri da leggere dal flusso |

### Valore di ritorno

Il numero di caratteri letti dal flusso di input

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BinaryReader](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)