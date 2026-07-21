---
title: HashSet
second_title: Справочник API Aspose.Slides для C++
description: Предварительное объявление класса HashSet.
type: docs
weight: 222
url: /ru/system.collections.generic/hashset/
---
## HashSet класс

Forward declaration of [HashSet](./) class.

```cpp
template<typename T>class HashSet : public System::Collections::Generic::BaseSet<T, std::unordered_set<T, EqualityComparerHashAdapter<T>, EqualityComparerAdapter<T>, System::Details::CollectionHelpers::ContainerPointerMode<T>::allocator_type>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual void [Add](../icollection/add/)(const T&) | Добавляет элемент в коллекцию. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Получает итератор, указывающий на первый элемент (если есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](../ienumerable/getenumerator/) возвращает копию объекта T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Получает итератор, указывающий на первый элемент (если есть) константного экземпляра коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Получает итератор, указывающий на первый константный элемент (если есть) коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Получает итератор, указывающий сразу после последнего константного элемента (если есть) коллекции. |
| virtual void [Clear](../icollection/clear/)() | Удаляет все элементы из коллекции. |
| virtual **bool** [Contains](../icollection/contains/)(const T&) const | Проверяет, присутствует ли элемент в коллекции. |
| virtual void [CopyTo](../icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)<T>, int) | Копирует все элементы коллекции в существующие элементы массива. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Получает итератор, указывающий сразу после последнего элемента (если есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](../ienumerable/getenumerator/) возвращает копию объекта T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Получает итератор, указывающий сразу после последнего элемента (если есть) константного экземпляра коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Только для внутренних целей. |
| virtual int [get_Count](../icollection/get_count/)() const | Получает количество элементов в коллекции. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../icollection/get_syncroot/)() const | Получает объект, через который синхронизируется коллекция. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [SharedPtr](../../system/sharedptr/)<[IEnumerator](../ienumerator/)<T>> [GetEnumerator](../ienumerable/getenumerator/)() | Получает перечислитель. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [HashSet](./hashset/)() | Информация RTTI. |
| [HashSet](./hashset/)(int) | Создаёт пустой набор с указанной ёмкостью. |
| [HashSet](./hashset/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../iequalitycomparer/)<T>>& ) | Создаёт пустой набор, использующий указанный сравнитель равенства. |
| [HashSet](./hashset/)(const [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>& ) | Создаёт hashset на основе перечисляемых значений. |
| [ICollection](../icollection/icollection/)() | Конструктор по умолчанию. |
| [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)&) | Конструктор копирования. |
| [ICollection](../icollection/icollection/)([ICollection](../icollection/)&&) | Конструктор перемещения. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Применяет функцию-аккумулятор к последовательности. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function<**bool**(T)>) | Определяет, существует ли хотя бы один элемент последовательности или удовлетворяет условию. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Cast](../ienumerable/linq_cast/)() | Преобразует элементы к указанному типу. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>>) | Конкатенирует две последовательности. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (вычисленное прямым подсчётом). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Возвращает количество элементов в последовательности, удовлетворяющих заданному условию. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_First](../ienumerable/linq_first/)() | Возвращает первый элемент последовательности. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Возвращает первый элемент последовательности, удовлетворяющий заданному условию. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Группирует элементы последовательности. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Группирует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Возвращает последний элемент последовательности. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Возвращает последний элемент последовательности или значение по умолчанию, если последовательность пуста. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_OfType](../ienumerable/linq_oftype/)() | Фильтрует элементы последовательности по указанному типу. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Сортирует элементы последовательности по возрастанию в соответствии со значениями ключей, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Сортирует элементы последовательности по убыванию в соответствии со значениями ключей, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Инвертирует порядок элементов в последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Преобразует каждый элемент последовательности в новую форму, включая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<ResultType>>> &) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Возвращает указанное количество непрерывных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)<[List](../list/)<T>> [LINQ_ToList](../ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../ienumerable/)<T>> [LINQ_Where](../ienumerable/linq_where/)(std::function<**bool**(T)>) | Фильтрует последовательность по указанному предикату. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-стража [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)&&) | Оператор перемещения присваивания. |
| [ICollection](../icollection/)& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)&) | Оператор перемещения присваивания. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Сравнивает объекты по ссылке. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Сравнивает объекты по ссылке. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Сравнивает объект типажа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| virtual **bool** [Remove](../icollection/remove/)(const T&) | Удаляет элемент из коллекции. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-стража [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Получает реализацию begin const iterator для текущего контейнера. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Получает реализацию begin iterator для текущего контейнера. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Получает реализацию end const iterator для текущего контейнера. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Получает реализацию end iterator для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) | Тип самого себя. |
| [BaseType](./basetype/) | Базовый тип. |
| [ThisPtr](./thisptr/) | Тип указателя. |

## Remarks

Реализация множества основана на хешировании. Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи в функции в качестве аргумента.

## See Also

* Класс [BaseSet](../baseset/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)