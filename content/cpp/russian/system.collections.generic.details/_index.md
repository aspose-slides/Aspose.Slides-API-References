---
title: "System::Collections::Generic::Details"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 352
url: /ru/system.collections.generic.details/
---
## Классы

| Класс | Описание |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable, используемый методами расширения IEnumerable.Cast() и IEnumerable.OfType(). |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable, используемый методом расширения IEnumerable.Select(). |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator, используемый методом расширения IEnumerable.Cast(). |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator, используемый методом расширения IEnumerable.OfType(). |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator, используемый методом расширения IEnumerable.Select(). |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |
## Структуры

| Структура | Описание |
| --- | --- |
| [ComparerType](./comparertype/) | Сравнивает элементы, используя семантику 'less'. |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | Сравнивает элементы, используя семантику 'less'. |
| [has_method_compareto](./has_method_compareto/) | Проверяет, существует ли метод CompareTo в указанном типе. Если да, наследует std::true_type, иначе наследует std::false_type. Может использоваться в std::enable_if. |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | Проверяет, существует ли метод CompareTo(SharedPtr<T>) в указанном типе. Если да, наследует std::true_type, иначе наследует std::false_type. Может использоваться в std::enable_if. |
| [IsEqualExist](./isequalexist/) | Проверяет, предоставляет ли тип оператор ==. |
## Функции

| Функция | Описание |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | Проверяет, выходит ли индекс за границы контейнера, исключая размер контейнера. |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | Проверяет, выходит ли индекс за границы контейнера, исключая размер контейнера. |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | Проверяет, выходит ли индекс за границы контейнера, включая размер контейнера. |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | Проверяет, выходит ли индекс за границы контейнера, включая размер контейнера. |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | Вспомогательная функция для определения, имеет ли конкретный класс оператор ==. |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | Вспомогательная функция для определения, имеет ли конкретный класс оператор ==. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Пытается получить первый элемент коллекции. |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | Пытается получить первый элемент коллекции, удовлетворяющий предикатной функции. |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | Пытается получить последний элемент коллекции. |
## Типedefы

| Типedef | Описание |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | Пустой typedef для проверки существования оператора ==. |