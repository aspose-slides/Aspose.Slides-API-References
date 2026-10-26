---
title: Sort()
second_title: Aspose.Slides C++ API-referencia
description: Rendezi a megadott tömb elemeit az alapértelmezett összehasonlító használatával.
type: docs
weight: 742
url: /hu/system/array/sort/
---
## Array::Sort(const ArrayPtr\<Type\>\&) metódus

Rendez egy megadott tömb elemeit az alapértelmezett összehasonlító használatával.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cél tömb |

## Array::Sort(const ArrayPtr\<Type\>\&, int, int) metódus

Rendez egy megadott tömb elemcsoportját az alapértelmezett összehasonlító használatával.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cél tömb |
| startIndex | int | Az index, amely a rendezendő elemtartomány elejét jelöli |
| count | int | A rendezendő elemtartomány mérete |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metódus

Rendez egy megadott tömb elemeit a megadott összehasonlító használatával.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cél tömb |
| comparator | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<T\>\>\& | IComparer<T> objektum, amely a tömb elemeit hasonlítja össze |

## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) metódus

NEM VALÓSÍTOTT.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```

## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) metódus

Rendez egy megadott tömb elemeit a megadott összehasonlítás használatával.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) metódus

Rendez két tömböt – az egyiket kulcsokat, a másikat a megfelelő elemeket tartalmazó tömböt – a kulcsokat tartalmazó tömb értékei alapján, amely elemeket az operator< használatával hasonlítanak össze.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A **keys** tömb elemeinek típusa |
| TValue | A **items** tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) amely kulcsértékeket tartalmaz |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) amely olyan elemeket tartalmaz, amelyek a **keys** tömb kulcsértékeihez vannak leképezve |

## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) metódus

Rendez két tömböt – az egyiket kulcsokat, a másikat a megfelelő elemeket tartalmazó tömböt – a kulcsokat tartalmazó tömb értékei alapján, amely elemeket az alapértelmezett összehasonlító használatával hasonlítanak össze.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| TKey | A **keys** tömb elemeinek típusa |
| TValue | A **items** tömb elemeinek típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| keys | const [ArrayPtr](../../arrayptr/)\<TKey\>\& | [Array](../) amely kulcsértékeket tartalmaz |
| items | const [ArrayPtr](../../arrayptr/)\<TValue\>\& | [Array](../) amely olyan elemeket tartalmaz, amelyek a **keys** tömb kulcsértékeihez vannak leképezve |
| index | int | Az index, amely a rendezendő tartomány kezdetét jelöli |
| length | int | A rendezendő tartomány elemeinek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Típusdefiníció [SharedPtr](../../sharedptr/)
* Metódus [Type](../../object/type/)
* Osztály [Array](../)
* Osztály [IComparer](../../../system.collections.generic/icomparer/)
* Osztály [Comparison](../../comparison/)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)