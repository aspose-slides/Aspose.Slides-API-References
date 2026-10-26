---
title: ConvertAll()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт список элементов, преобразованных к другому типу.
type: docs
weight: 352
url: /ru/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) метод


Создаёт список элементов, преобразованных к другому типу.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| OutputType | Тип элемента списка-вывода. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Конвертер, используемый для преобразования элементов. |

### Возвращаемое значение

Новосозданный список преобразованных элементов.

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [Converter](../../../system/converter/)
* класс [List](../)
* пространство имён [System::Collections::Generic](../../)
* библиотека [Aspose.Slides](../../../)