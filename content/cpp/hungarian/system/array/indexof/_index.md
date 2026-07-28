---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a megadott elem első előfordulásának indexét a tömbben.
type: docs
weight: 131
url: /hu/system/array/indexof/
---
## Array::IndexOf(const T\&) const metódus


Meghatározza a megadott elem első előfordulásának indexét a tömbben.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | Az elem indexe, amelyet meg kell határozni |

### Visszatérési érték

[Index](../../index/) az első előfordulás indexe a megadott elem esetén, ha az elem megtalálható, egyébként -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metódus


Meghatározza a megadott elem első előfordulásának indexét a tömbben.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | A tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meg kell határozni |

### Visszatérési érték

[Index](../../index/) az első előfordulás indexe a megadott elem esetén, ha az elem megtalálható, egyébként -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metódus


Meghatározza a megadott elem első előfordulásának indexét a tömbben a megadott indextől kezdve.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | A tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meg kell határozni |
| startIndex | int | [Index](../../index/) ahol a keresés elindul |

### Visszatérési érték

[Index](../../index/) az első előfordulás indexe a megadott elem esetén, ha az elem megtalálható, egyébként -1

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metódus


Meghatározza a megadott elem első előfordulásának indexét a tömb egy tartományában, amelyet a kezdő index és a tartomány elemeinek száma határoz meg.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | A tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meg kell határozni |
| startIndex | int | [Index](../../index/) ahol a keresés elindul |
| count | int | A keresendő tartomány elemeinek száma |

### Visszatérési érték

[Index](../../index/) az első előfordulás indexe a megadott elem esetén, ha az elem megtalálható, egyébként -1

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Osztály [Array](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)