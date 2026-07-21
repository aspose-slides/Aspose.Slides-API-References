---
title: ListExt
second_title: Aspose.Slides для C++ справочник API
description: обобщённый класс List, реализующий интерфейс IListWrapper
type: docs
weight: 443
url: /ru/system.collections.generic/listext/
---
## ListExt класс

обобщённый [List](../list/) класс, реализующий интерфейс [IListWrapper](../../system.collections/ilistwrapper/)

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Методы

| Метод | Описание |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | Специфично для C++. |
| void [Add](../list/add/)(const T\&) override | Добавляет элемент в конец списка. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Добавляет элементы в список; используется при переводе инициализаторов. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Добавляет все элементы из коллекции (или из себя) в конец текущего списка. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Получает ссылку только для чтения на эту коллекцию. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Получает итератор на первый элемент коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Получает итератор на первый элемент константно-квалифицированной коллекции. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Ищет элемент в отсортированном списке. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Получает итератор на первый константно-квалифицированный элемент коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Получает итератор для несуществующего константно-квалифицированного элемента за концом коллекции. |
| void [Clear](../list/clear/)() override | Удаляет все элементы. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Проверяет, присутствует ли элемент в списке. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Создаёт список элементов, преобразованных в другой тип. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Копирует элементы списка в существующие элементы массива. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Копирует все элементы в существующие элементы массива. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Копирует элементы, начиная с указанного индекса, в существующие элементы массива. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Получает обратный итератор к последнему константно-квалифицированному элементу коллекции (первому в обратном порядке). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | реализация интерфейса [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | вспомогательная функция реализации [IListWrapper](../../system.collections/ilistwrapper/) для ссылочных типов. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | вспомогательная функция реализации [IListWrapper](../../system.collections/ilistwrapper/) для типовых значений. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | вспомогательная функция реализации [IListWrapper](../../system.collections/ilistwrapper/) для других типов. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Получает обратный итератор для несуществующего константно-квалифицированного элемента перед началом коллекции. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Функция доступа к базовой структуре данных. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Функция доступа к базовой структуре данных. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Получает итератор для несуществующего элемента за концом коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Получает итератор для несуществующего элемента за концом константно-квалифицированной коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Проверяет, существует ли элемент, удовлетворяющий определённому предикату, в списке. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, удовлетворяющий конкретному предикату. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элементы, удовлетворяющие конкретному предикату. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, удовлетворяющий конкретному предикату. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, удовлетворяющий конкретному предикату. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, удовлетворяющий конкретному предикату. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет последний элемент, удовлетворяющий конкретному предикату. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Применяет действие ко всем элементам списка. |
| int [get_Capacity](../list/get_capacity/)() const | Получает текущую ёмкость списка. |
| int [get_Count](../list/get_count/)() const override | Получает количество элементов в текущем списке. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Проверяет, является ли коллекция фиксированного размера. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Получает объект, через который происходит синхронизация коллекции. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Получает перечислитель для перебора элементов списка. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Создаёт срез списка. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Конструктор по умолчанию. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Конструктор копирования. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Конструктор перемещения. |
| T [idx_get](../list/idx_get/)(int) const override | Получает элемент по указанной позиции. |
| void [idx_set](../list/idx_set/)(int, T) override | Устанавливает элемент в указанной позиции. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Получает первый индекс конкретного элемента. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Ищет конкретный элемент в списке. |
| void [Insert](../list/insert/)(int, const T\&) override | Вставляет элемент в указанную позицию. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Вставляет диапазон данных в указанную позицию. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения во всём списке. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](../list/), который простирается от первого элемента до указанного индекса. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](../list/), который содержит указанное количество элементов и заканчивается на указанном индексе. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Применяет функцию аккумулятора к последовательности. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Определяет, содержит ли последовательность любые элементы. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет условию. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Преобразует элементы к указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Конкатенирует две последовательности. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (вычисляется прямым подсчётом). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Возвращает количество элементов в последовательности, удовлетворяющих указанному условию. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_First](../ienumerable/linq_first/)() | Возвращает первый элемент последовательности. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Возвращает первый элемент последовательности, удовлетворяющий указанному условию. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Группирует элементы последовательности. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Группирует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Возвращает последний элемент последовательности. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Возвращает последний элемент последовательности или значение по умолчанию, если последовательность пуста. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщенной последовательности и возвращает максимальное полученное значение. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщенной последовательности и возвращает минимальное полученное значение. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Фильтрует элементы последовательности по указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по возрастанию в соответствии со значениями ключа, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по убыванию в соответствии со значениями ключа, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Инвертирует порядок элементов в последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Возвращает указанное количество последовательных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Фильтрует последовательность по указанному предикату. |
|  [List](../list/list/)() | Создаёт пустой список. |
|  [List](../list/list/)(int) | Создаёт список с заранее определённой ёмкостью. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Конструктор копирования. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Оператор перемещения присваивания. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Оператор перемещения присваивания. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Функция доступа. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Функция доступа. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Получает обратный итератор к последнему элементу коллекции (первому в обратном порядке). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Получает обратный итератор к последнему элементу константно-квалифицированной коллекции (первому в обратном порядке). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](../list/remove/)(const T\&) override | Удаляет первое вхождение конкретного элемента из списка. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Удаляет все элементы, соответствующие конкретному предикату. |
| void [RemoveAt](../list/removeat/)(int) override | Удаляет элемент в указанной позиции. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [RemoveRange](../list/removerange/)(int, int) | Удаляет срез списка. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Получает обратный итератор для несуществующего элемента перед началом коллекции. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Получает обратный итератор для несуществующего элемента перед началом константно-квалифицированной коллекции. |
| void [Reverse](../list/reverse/)() | Разворачивает порядок элементов всего списка. |
| void [Reverse](../list/reverse/)(int, int) | Разворачивает порядок элементов среза списка. |
| void [set_Capacity](../list/set_capacity/)(int) | Устанавливает ёмкость списка. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Сортирует элементы в списке. |
| void [Sort](../list/sort/)() | Сортирует элементы в списке с использованием компаратора по умолчанию. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Сортирует элементы в срезе списка. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Сортирует элементы в списке. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Преобразует список в массив. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [TrimExcess](../list/trimexcess/)() | Устанавливает ёмкость списка в соответствии с её размером. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Определяет, соответствует ли каждый элемент коллекции условиям, определённым указанным предикатом. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Получает реализацию начального константного итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Получает реализацию начального итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Получает реализацию конечного константного итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Получает реализацию конечного итератора для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Разрушает объект. Освобождает все внутренние структуры данных. |

## Типовые определение

| Типовое определение | Описание |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## См. также

* Класс [List](../list/)
* Класс [IListWrapper](../../system.collections/ilistwrapper/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)