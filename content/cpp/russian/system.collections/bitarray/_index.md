---
title: BitArray
second_title: Aspose.Slides for C++ Справочник API
description: "Массив бит, к которым можно обращаться по индексу. Объекты этого класса следует выделять только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или ошибкам утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1
url: /ru/system.collections/bitarray/
---
## BitArray класс

[Array](../../system/array/) бит, которые можно адресовать по индексу. Объекты этого класса следует выделять только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или ошибкам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его функциям в качестве аргумента.

```cpp
class BitArray : public virtual System::Object,
                 public System::Collections::Generic::ICollection<bool>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Add](./add/)(const **bool**\&) override | Добавляет значение в конец контейнера. |
| [BitArrayPtr](../bitarrayptr/) [And](./and/)(const [BitArrayPtr](../bitarrayptr/)\&) | Вычисляет побитовое 'and' между двумя BitSet'ами. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Получает итератор, указывающий на первый элемент (если он существует) коллекции. Этот итератор нельзя использовать для изменения ссылки на объект, потому что [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает объект-копию типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Получает итератор, указывающий на первый элемент (если он существует) константно-квалифицированного экземпляра коллекции. |
|  [BitArray](./bitarray/)(const [bitset](./bitset/)\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(const [BitArray](./)\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(const [BitArrayPtr](../bitarrayptr/)\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**bool**\>\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<int\>\&) | Конструктор копирования. |
|  [BitArray](./bitarray/)(int, **bool**) | Конструктор заполнения. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Получает итератор, указывающий на первый константно-квалифицированный элемент (если он существует) коллекции. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Получает итератор, указывающий сразу после последнего константно-квалифицированного элемента (если он существует) коллекции. |
| void [Clear](./clear/)() override | Удаляет все элементы. |
| **bool** [Contains](./contains/)(const **bool**\&) const override | Проверяет, присутствует ли конкретное значение в контейнере. Не реализовано. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<**bool**\>, int) override | Копирует данные в существующие элементы массива. |
| [bitset](./bitset/)\& [data](./data/)() | Доступ к внутренней структуре данных. |
| const [bitset](./bitset/)\& [data](./data/)() const | Доступ к внутренней структуре данных. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Получает итератор, указывающий сразу после последнего элемента (если он существует) коллекции. Этот итератор нельзя использовать для изменения ссылки на объект, потому что [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает объект-копию типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Получает итератор, указывающий сразу после последнего элемента (если он существует) константно-квалифицированного экземпляра коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [Get](./get/)(int) const | Получает элемент [BitArray](./). |
| int [get_Count](./get_count/)() const override | Получает размер контейнера. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| int [get_Length](./get_length/)() const | Получает размер контейнера. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Получает объект, через который происходит синхронизация коллекции. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<**bool**\>\> [GetEnumerator](./getenumerator/)() override | Создаёт объект-перечислитель. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../../system.collections.generic/icollection/icollection/)() | Конструктор по умолчанию. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Конструктор копирования. |
|  [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Конструктор перемещения. |
| **bool** [idx_get](./idx_get/)(int) const | Функция-геттер. |
| void [idx_set](./idx_set/)(int, **bool**) | Функция-сеттер. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Применяет функцию-накопитель к последовательности. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет условию. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Приводит элементы к указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Конкатенирует две последовательности. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (подсчитано прямым подсчётом). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Возвращает количество элементов последовательности, удовлетворяющих заданному условию. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Возвращает первый элемент последовательности. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Возвращает первый элемент последовательности, удовлетворяющий заданному условию. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Группирует элементы последовательности. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Группирует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Возвращает последний элемент последовательности. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Возвращает последний элемент последовательности или значение по умолчанию, если последовательность пуста. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Фильтрует элементы последовательности по указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по возрастанию в соответствии с ключами, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по убыванию в соответствии с ключами, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Инвертирует порядок элементов последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Возвращает указанное количество последовательных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Фильтрует последовательность по указанному предикату. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [BitArrayPtr](../bitarrayptr/) [Not](./not/)() | Инвертирует BitSet. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. Не копирует ничего, а просто инициализирует новый объект и позволяет копировать подклассы. |
| **bool** [operator!=](./operator_not_equal/)(const [BitArray](./)\&) const | Побитовый оператор сравнения. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. Не копирует ничего, а просто инициализирует новый объект и позволяет копировать подклассы. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Оператор перемещения присваивания. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Оператор перемещения присваивания. |
| **bool** [operator==](./operator_equal_equal/)(const [BitArray](./)\&) const | Побитовый оператор сравнения. |
| **Reference** [operator[]](./operator[]/)(int) | Функция-доступ. |
| [BitArrayPtr](../bitarrayptr/) [Or](./or/)(const [BitArrayPtr](../bitarrayptr/)\&) | Вычисляет побитовое 'or' между двумя BitSet'ами. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](./remove/)(const **bool**\&) override | Возвращает первое вхождение указанного значения. Не реализовано. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [Set](./set/)(int, **bool**) | Устанавливает элемент [BitArray](./). |
| void [SetAll](./setall/)(**bool**) | Устанавливает все элементы в указанное значение. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Формальная реализация механизма слабых шаблонных аргументов; неприменимо к этому классу. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<**bool**\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Получает реализацию const-итератора begin для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<**bool**\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Получает реализацию итератора begin для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<**bool**\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Получает реализацию const-итератора end для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<**bool**\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Получает реализацию итератора end для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| [BitArrayPtr](../bitarrayptr/) [Xor](./xor/)(const [BitArrayPtr](../bitarrayptr/)\&) | Вычисляет побитовое 'xor' между двумя BitSet'ами. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [bitset](./bitset/) | Базовый тип данных. |

## Примечания

```cpp
#include <system/collections/bitarray.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void Print(const System::SmartPtr<System::Collections::Generic::IEnumerable<bool>> &bitArray)
{
  for (const auto item: bitArray)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Создаёт новый экземпляр класса BitArray.
  auto bitArray = MakeObject<System::Collections::BitArray>(3);

  // Печатает значения.
  Print(bitArray);

  return 0;
}
/*
Этот пример кода выводит следующее:
0 0 0
*/
```

## См. также

* Класс [Object](../../system/object/)
* Класс [ICollection](../../system.collections.generic/icollection/)
* Пространство имён [System::Collections](../)
* Библиотека [Aspose.Slides](../../)