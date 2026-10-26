---
title: CopyTo()
second_title: Aspose.Slides C++ API referencia
description: A listaelemeket létező tömbelemekbe másolja.
type: docs
weight: 209
url: /hu/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) metódus


A listaelemeket létező tömbelemekbe másolja.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Cél tömb. |
| arrayIndex | int | A cél tömb kezdőindexe. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) metódus


Az összes elemet létező tömbelemekbe másolja.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) ahová az elemek másolásra kerülnek. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) metódus


Az elemeket a megadott indextől kezdve létező tömbelemekbe másolja.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Az aktuális objektum által reprezentált listában lévő elem 0-alapú indexe, amelytől a másolás kezdődik |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) ahová az elemek másolásra kerülnek. |
| arrayIndex | int | Kezdőpozíció a cél tömbben. |
| count | int | A másolandó elemek száma. |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [List](../)
* Névtere [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)