---
title: LastIndexOf()
second_title: Aspose.Slides for C++ API hivatkozás
description: Meghatározza a megadott elem utolsó előfordulásának indexét a tömb egy tartományában, amelyet a kezdő index és a tartomány elemeinek száma határoz meg.
type: docs
weight: 703
url: /hu/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metódus

Meghatározza a megadott elem utolsó előfordulásának indexét egy tartományban lévő tömb elemei között, amelyet a kezdőindex és a tartomány elemeinek száma határoz meg.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | a tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meghatározni kell |
| startIndex | int | [Index](../../index/) az a pozíció, ahol a keresés elindul |
| count | int | A keresendő tartomány elemeinek száma |

### Visszatérési érték

[Index](../../index/) a megadott elem utolsó előfordulásának indexe, ha az elem megtalálható, egyébként -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metódus

Meghatározza a megadott elem utolsó előfordulásának indexét a tömbben, a megadott indextől kiindulva.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | a tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meghatározni kell |
| startIndex | int | [Index](../../index/) az a pozíció, ahol a keresés elindul |

### Visszatérési érték

[Index](../../index/) a megadott elem utolsó előfordulásának indexe, ha az elem megtalálható, egyébként -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metódus

Meghatározza a megadott elem utolsó előfordulásának indexét a tömbben.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| ArrayType | A cél tömb elemeinek típusa |
| ValueType | a tömbben keresendő elem típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) a megadott elem kereséséhez |
| value | const [ValueType](../valuetype/)\& | Az elem indexe, amelyet meghatározni kell |

### Visszatérési érték

[Index](../../index/) a megadott elem utolsó előfordulásának indexe, ha az elem megtalálható, egyébként -1

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Osztály [Array](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)