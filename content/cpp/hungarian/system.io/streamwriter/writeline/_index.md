---
title: WriteLine()
second_title: Aspose.Slides C++ API-referencia
description: A sorvége karaktereket írja a folyamra.
type: docs
weight: 92
url: /hu/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metódus

A sorvége karaktereket írja a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metódus

Az adott karakterláncot írja a sorvége karakterekkel együtt a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A kiírandó karakterlánc |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metódus

Az adott objektum karakterlánc ábrázolását írja a sorvége karakterekkel együtt a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | A kiírandó objektum |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metódus

Az adott tömb összes karakterét írja a sorvége karakterekkel együtt a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | A kiírandó karaktereket tartalmazó tömb |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus

Az adott karaktertömbből a megadott UTF-16 karakterek részhalmazát írja a sorvége karakterekkel együtt a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | A kiírandó karaktereket tartalmazó tömb |
| index | **int32_t** | A **buffer** tömbben a kiírandó részhalmaz kezdőhelyének 0-bázisú indexe |
| count | **int32_t** | A kiírandó részhalmazban lévő karakterek száma; a -1 azt jelzi, hogy a részhalmaz a **buffer** tömb végénél ér véget |

## StreamWriter::WriteLine(const char_t *) metódus

Az adott C-karakterláncot írja a sorvége karakterekkel együtt a folyamra.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const char_t * | A kiírandó C-karakterlánc |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metódus

Az adott objektum karakterlánc ábrázolását írja a sorvége karakterekkel együtt a folyamra.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Az objektum típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | A kiírandó objektum |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [StreamWriter](../)
* Osztály [String](../../../system/string/)
* Osztály [Object](../../../system/object/)
* Névtér [System::IO](../../)
* Library [Aspose.Slides](../../../)