---
title: MakeDiff()
second_title: Справочник API Aspose.Slides для C++
description: Вычисляет 'diff' между двумя коллекциями. Для каждого элемента каждой коллекции в качестве ключа получаемое значение будет положительным, если элемент встречается больше раз в \"ожидаемой\" коллекции, отрицательным, если элемент встречается больше раз в \"фактической\" коллекции, и нулевым, если элемент встречается одинаковое количество раз в каждой коллекции.
type: docs
weight: 1
url: /ru/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) метод

Вычисляет «разницу» между двумя коллекциями. Для каждого элемента каждой коллекции в качестве ключа получаемое значение будет положительным, если элемент встречается больше раз в \"ожидаемой\" коллекции, отрицательным, если элемент встречается больше раз в \"фактической\" коллекции, и нулевым, если элемент встречается одинаковое количество раз в каждой коллекции.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Expected collection element type. |
| T2 | Actual collection element type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Expected collection. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Actual collecion. |

### Возвращаемое значение

Map результатов сравнения по каждому значению в соответствии с вышеуказанными правилами.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Dictionary](../../../system.collections.generic/dictionary/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Структура [CollectionAssertHelper](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)