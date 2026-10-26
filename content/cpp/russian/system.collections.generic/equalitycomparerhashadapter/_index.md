---
title: EqualityComparerHashAdapter
second_title: Справочник API Aspose.Slides для C++
description: Адаптер для использования IEqualityComparer при вычислении хеша. Использует объект сравнения, если он установлен; в противном случае использует доступный метод хеширования, выбранный с помощью структуры DictionaryHashSelector.
type: docs
weight: 677
url: /ru/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter структура


Адаптер для использования [IEqualityComparer](../iequalitycomparer/) при вычислении хеша. Использует объект сравнения, если он установлен; в противном случае использует доступный метод хеширования, выбранный с помощью структуры [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| Hashed | тип. |
## Методы

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | Создает адаптер без сравнивателя для использования. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Создает адаптер с заданным сравнивателем для использования. |
| std::size_t [operator()](./operator_call/)(const T\&) const | Вычисляет значение хеша. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Устанавливает сравниватель для использования. |

## См. также

* Пространство имен [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)