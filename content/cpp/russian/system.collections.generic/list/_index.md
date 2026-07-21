---
title: List
second_title: Aspose.Slides for C++ — справочник API
description: Предварительное объявление List.
type: docs
weight: 430
url: /ru/system.collections.generic/list/
---
## List класс


[List](./) предварительное объявление.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Специфично для C++. |
| void [Add](./add/)(const T\&) override | Добавляет элемент в конец списка. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Добавляет элементы в список; используется при преобразовании инициализаторов. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Добавляет все элементы из коллекции (или из себя) в конец текущего списка. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Получает только для чтения ссылку на эту коллекцию. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Получает итератор к первому элементу коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Получает итератор к первому элементу константно-квалифицированной коллекции. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Ищет элемент в отсортированном списке. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Ищет элемент в отсортированном списке. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Получает итератор к первому элементу коллекции, квалифицированному const. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Получает итератор для несуществующего const-квалифицированного элемента за концом коллекции. |
| void [Clear](./clear/)() override | Удаляет все элементы. |
| **bool** [Contains](./contains/)(const T\&) const override | Проверяет, присутствует ли элемент в списке. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Создаёт список элементов, преобразованных в другой тип. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Копирует элементы списка в существующие элементы массива. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Копирует все элементы в существующие элементы массива. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Копирует элементы, начиная с указанного индекса, в существующие элементы массива. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Получает обратный итератор к последнему const-квалифицированному элементу коллекции (первому в обратном порядке). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Получает обратный итератор для несуществующего const-квалифицированного элемента перед началом коллекции. |
| [vector_t](./vector_t/)\& [data](./data/)() | Функция доступа к базовой структуре данных. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Функция доступа к базовой структуре данных. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Получает итератор для несуществующего элемента за концом коллекции. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Получает итератор для несуществующего элемента за концом const-квалифицированной коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Проверяет, существует ли элемент, соответствующий определенному предикату, в списке. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, соответствующий определенному предикату. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элементы, соответствующие определенному предикату. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, соответствующий определенному предикату. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, соответствующий определенному предикату. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Ищет элемент, соответствующий определенному предикату. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Ищет последний элемент, соответствующий определенному предикату. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Применяет действие ко всем элементам списка. |
| int [get_Capacity](./get_capacity/)() const | Получает текущую ёмкость списка. |
| int [get_Count](./get_count/)() const override | Получает количество элементов в текущем списке. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Проверяет, имеет ли коллекция фиксированный размер. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Получает объект, через который синхронизируется коллекция. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Получает перечислитель для перебора элементов списка. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Создаёт срез списка. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Конструктор по умолчанию. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Конструктор копирования. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Конструктор перемещения. |
| T [idx_get](./idx_get/)(int) const override | Получает элемент в указанной позиции. |
| void [idx_set](./idx_set/)(int, T) override | Устанавливает элемент в указанной позиции. |
| int [IndexOf](./indexof/)(const T\&) const override | Получает первый индекс указанного элемента. |
| int [IndexOf](./indexof/)(const T\&, int) const | Ищет указанный элемент в списке. |
| void [Insert](./insert/)(int, const T\&) override | Вставляет элемент в указанную позицию. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Вставляет диапазон данных в указанную позицию. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в полном списке. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](./), который охватывает от первого элемента до указанного индекса. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](./), который содержит указанное количество элементов и заканчивается на указанном индексе. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Применяет функцию-аккумулятор к последовательности. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет ли он условию. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Преобразует элементы к указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Конкатенирует две последовательности. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (вычисленное прямым подсчётом). |
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
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по возрастанию согласно значениям ключа, выбранным keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по убыванию согласно значениям ключа, выбранным keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Инвертирует порядок элементов в последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Возвращает указанное число последовательных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Фильтрует последовательность по указанному предикату. |
|  [List](./list/)() | Создаёт пустой список. |
|  [List](./list/)(int) | Creates list with pre-defined capacity. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Конструктор копирования. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или через объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Оператор перемещающего присваивания. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Оператор перемещающего присваивания. |
| vector_t::reference [operator[]](./operator[]/)(int) | Функция доступа. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Функция доступа. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Получает обратный итератор к последнему элементу коллекции (первому в обратном порядке). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Получает обратный итератор к последнему элементу const-квалифицированной коллекции (первому в обратном порядке). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](./remove/)(const T\&) override | Удаляет первое вхождение указанного элемента из списка. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Удаляет все элементы, соответствующие указанному предикату. |
| void [RemoveAt](./removeat/)(int) override | Удаляет элемент в указанной позиции. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [RemoveRange](./removerange/)(int, int) | Удаляет срез списка. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Получает обратный итератор для несуществующего элемента перед началом коллекции. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Получает обратный итератор для несуществующего элемента перед началом const-квалифицированной коллекции. |
| void [Reverse](./reverse/)() | Разворачивает порядок элементов во всём списке. |
| void [Reverse](./reverse/)(int, int) | Разворачивает порядок элементов в срезе списка. |
| void [set_Capacity](./set_capacity/)(int) | Устанавливает ёмкость списка. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый параметр шаблона как weak-указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Сортирует элементы в списке. |
| void [Sort](./sort/)() | Сортирует элементы в списке, используя компаратор по умолчанию. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Сортирует элементы в срезе списка. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Сортирует элементы в списке. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Конвертирует список в массив. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [TrimExcess](./trimexcess/)() | Устанавливает ёмкость списка равной её размеру. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Определяет, соответствует ли каждый элемент в коллекции условиям, заданным указанным предикатом. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или через объект-страж [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию begin-итератора const для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию begin-итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию end-итератора const для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию end-итератора для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Типы

| Тип | Описание |
| --- | --- |
| [ValueType](./valuetype/) | Этот тип. |
| [BaseType](./basetype/) | Тип интерфейса. |
| [vector_t](./vector_t/) | Базовый тип данных. |
| [iterator](./iterator/) | Тип итератора. |
| [const_iterator](./const_iterator/) | Тип константного итератора. |
| [reverse_iterator](./reverse_iterator/) | Тип обратного итератора. |
| [const_reverse_iterator](./const_reverse_iterator/) | Тип константного обратного итератора. |
| [IEnumerablePtr](./ienumerableptr/) | Контейнер, содержащий элементы того же типа, что и мы. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** тип. |
## Замечания

[List](./) - обёртка вокруг std::vector для использования в переводимом коде. Требуется, чтобы оператор == был реализован для типа элемента. Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Создать первый список.
  auto list1 = MakeObject<List<int>>();

  // Заполнить первый список.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Сортировать первый список.
  // Элементы первого списка будут: {-5, 1, 3, 8}
  list1->Sort();

  // Удалить элемент с индексом 2.
  // Элементы первого списка будут: {-5, 1, 8}
  list1->RemoveAt(2);

  // Вставить элемент в позицию 1.
  // Элементы первого списка будут: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Создать второй список.
  auto list2 = MakeObject<List<int>>();

  // Заполнить второй список.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Добавить элементы из второго списка к первому.
  list1->AddRange(list2);

  // Вывести элементы первого списка.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Этот пример кода выводит следующее:
- 5 15 1 8 10 20 30
*/
```

## См. также

* Класс [Object](../../system/object/)
* Класс [IList](../ilist/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)