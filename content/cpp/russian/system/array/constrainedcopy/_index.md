---
title: ConstrainedCopy()
second_title: Aspose.Slides для C++ справочник API
description: Копирует диапазон элементов из System.Array, начиная с указанного источника.
type: docs
weight: 716
url: /ru/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) метод


Копирует диапазон элементов из [System.Array](../) начиная с указанного источника.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | Source array |
| srcIndex | **int64_t** | Index in the source array designating the beginning of the range of items to copy |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | Destination array |
| dstIndex | **int64_t** | Index in destination array to start inserting copied items at |
| count | **int64_t** | The number of elements to copy |
## Примечание


ВРЕМЕННАЯ НЕОБРАБАТАННАЯ РЕАЛИЗАЦИЯ БЕЗ ЛЮБЫХ ДОПОЛНЕНИЙ! 
## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [Array](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)