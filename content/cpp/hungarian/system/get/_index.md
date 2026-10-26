---
title: Get()
second_title: Aspose.Slides C++ API referencia
description: Függvény a megadott tuple N. elemének lekérdezésére. Túlterhelés az alapobjektumhoz.
type: docs
weight: 2406
url: /hu/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) függvény

Függvény egy adott tuple N. elemének lekérdezésére. Túlterhelés az alapobjektumhoz.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | elem index. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | ellenőrzendő objektum. |

### Visszatérési érték

Az N. tuple elem értéke, objektumra konvertálva.

## System::Get(const T\&) függvény

Függvény egy adott tuple N. elemének lekérdezésére. Túlterhelés olyan objektumokhoz, amelyek rendelkeznek Deconstruct metódussal.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | elem index. |
| T | ellenőrzött objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | const T\& | ellenőrzendő objektum. |

### Visszatérési érték

Az N. tuple elem értéke.

## System::Get(const SharedPtr\<T\>\&) függvény

Függvény egy adott tuple N. elemének lekérdezésére. Túlterhelés megosztott pointerekhez.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | elem index. |
| T | ellenőrzött objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | ellenőrzendő objektum. |

### Visszatérési érték

Az N. tuple elem értéke.

## System::Get(T\&, const Index\&) függvény

Megvalósítás a collection[index] kifejezésekhez.

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Gyűjtemény típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collection | T\& | Gyűjtemény objektum. |
| index | const [Index](../index/)\& | Elem index, típusa [System.Index](../index/). |

### Visszatérési érték

A számított eltolás szerinti gyűjteményelem.

## System::Get(T\&, const Range\&) függvény

Visszaad egy szeletet a megadott gyűjteményből, amelyet a megadott tartomány definiál.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collection | T\& | A szeletelendő gyűjtemény. |
| range | const [Range](../range/)\& | A tartomány, amely meghatározza a szelet határait. |

### Visszatérési érték

A gyűjtemény egy nézete vagy szelete a számított kezdő eltolástól és hosszúságtól.

## System::Get(const ValueTuple\<Args...\>\&) függvény

Lekéri a value tuple N. elemét.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| N | elem index. |
| Args | tuple elemei. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| tuple | const [ValueTuple](../valuetuple/)\<Args...\>\& | elem lekérdezéséhez használt tuple. |

### Visszatérési érték

Az N. tuple elem értéke.

## Lásd még

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Index](../index/)
* Class [Range](../range/)
* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)