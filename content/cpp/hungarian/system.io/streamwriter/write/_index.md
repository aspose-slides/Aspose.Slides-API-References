---
title: Write()
second_title: Aspose.Slides C++ API referencia
description: A megadott karaktert írja a folyamba.
type: docs
weight: 79
url: /hu/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metódus


A megadott karaktert írja a folyamba.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char_t | Az írandó karakter |

## StreamWriter::Write(const String\&) metódus


A megadott karakterláncot írja a folyamba.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Az írandó karakterlánc |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metódus


A megadott objektum karakterlánc ábrázolását írja a folyamba.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az írandó objektum |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metódus


Az összes karaktert írja a megadott tömbből a folyamba.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus


A megadott karaktertömbből a megadott UTF-16 karaktertartományt írja a folyamba.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |
| index | **int32_t** | A **buffer** tömbben a 0-tól indexelt elem, ahol a írandó részlet kezdődik |
| count | **int32_t** | A részletben írandó karakterek száma; a -1 azt jelzi, hogy a részlet a **buffer** tömb végénél ér véget |

## StreamWriter::Write(const char_t *) metódus


A megadott c-karakterláncot írja a folyamba.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const char_t * | Az írandó c-karakterlánc |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metódus


A megadott objektum karakterlánc ábrázolását írja a folyamba.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Az írandó objektum |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)