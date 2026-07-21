---
title: ConcurrentDictionary
second_title: Aspose.Slides для C++ справочник API
description: "Реализация словаря с поддержкой потокобезопасности. Объекты этого класса следует выделять только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приводит к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1
url: /ru/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary класс

Thread-safe dictionary implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

## Методы

| Метод | Описание |
| --- | --- |
| void [Add](./add/)(const TKey&, const TValue&) override | Добавляет значение в словарь. |
| virtual void [Add](../../system.collections.generic/idictionary/add/)(const TKey&, const TValue&) | Добавляет пару ключ-значение в контейнер. |
| virtual void [Add](../../system.collections.generic/icollection/add/)(const T&) | Добавляет элемент в коллекцию. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Возвращает итератор, указывающий на первый элемент (если он есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает объект-копию типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Возвращает итератор, указывающий на первый элемент (если он есть) константного экземпляра коллекции. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Возвращает итератор, указывающий на первый константный элемент (если он есть) коллекции. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Возвращает итератор, указывающий сразу после последнего константного элемента (если он есть) коллекции. |
| void [Clear](./clear/)() override | Удаляет все элементы в контейнере. |
| virtual **bool** [Contains](../../system.collections.generic/icollection/contains/)(const T&) const | Проверяет, присутствует ли элемент в коллекции. |
| virtual **bool** [ContainsKey](../../system.collections.generic/idictionary/containskey/)(const TKey&) const | Проверяет, содержит ли контейнер ключ. |
| void [CopyTo](./copyto/)([ArrayPtr](../../system/arrayptr/)<[System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | Копирует элементы контейнера в существующие элементы массива. |
| void [CopyTo](../../system.collections.generic/idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)<[KeyValuePair](../../system.collections.generic/keyvaluepair/)<TKey, TValue>>, int) override | Копирует содержимое словаря в существующие элементы массива. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)() | Создаёт пустой словарь. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [map_t](../../system.collections.generic/dictionary/map_t/)&) | Копирует данные из карты. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int) | Перегрузка, соответствующая созданию предварительно выделенного словаря; фактически не выполняет выделения. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>> &) | Конструктор копирования. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IDictionary](../../system.collections.generic/idictionary/)<TKey, TValue>>&, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>&) | Конструктор копирования. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>& ) | Создаёт пустой словарь. |
| [Dictionary](../../system.collections.generic/dictionary/dictionary/)(int, const [SharedPtr](../../system/sharedptr/)<[IEqualityComparer](../../system.collections.generic/iequalitycomparer/)<TKey>>& ) | Создаёт пустой словарь. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Возвращает итератор, указывающий сразу после последнего элемента (если он есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает объект-копию типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Возвращает итератор, указывающий сразу после последнего элемента (если он есть) константного экземпляра коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if<[IsSmartPtr](../../system/issmartptr/)<T1>::value&&[IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T1>::value&&![IsSmartPtr](../../system/issmartptr/)<T2>::value, **bool**>::type [Equals](../../system/object/equals/)(T1 const&, T2 const&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const&, **float** const&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const&, **double** const&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase&, void **) const | Только для внутреннего использования. |
| virtual int [get_Count](../../system.collections.generic/icollection/get_count/)() const | Возвращает количество элементов в коллекции. |
| **bool** [get_IsFixedSize](../../system.collections.generic/idictionary/get_isfixedsize/)() const | Проверяет, фиксирован ли размер коллекции. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| **bool** [get_IsSynchronized](../../system.collections.generic/idictionary/get_issynchronized/)() const | Проверяет, является ли контейнер потокобезопасным. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TKey>> [get_Keys](../../system.collections.generic/idictionary/get_keys/)() const | Получает коллекцию ключей. |
| [SharedPtr](../../system/sharedptr/)<typename [ThisType::KeyCollection](../../system.collections.generic/dictionary/keycollection/)> [get_KeysInternal](./get_keysinternal/)() const override | Возвращает обёрнутую коллекцию для доступа к ключам словаря. |
| [SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Возвращает объект, через который синхронизирована коллекция. |
| virtual [SharedPtr](../../system/sharedptr/)<[ICollection](../../system.collections.generic/icollection/)<TValue>> [get_Values](../../system.collections.generic/idictionary/get_values/)() const | Получает коллекцию значений. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, ассоциированную с объектом. |
| [IEnumeratorPtr](../../system.collections.generic/dictionary/ienumeratorptr/) [GetEnumerator](../../system.collections.generic/dictionary/getenumerator/)() override | Создаёт объект-перечислитель. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Обеспечивает хеширование пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&) const | Возвращает значение, если найдено; иначе **Value()**. |
| virtual TValue [GetValueOrDefault](../../system.collections.generic/idictionary/getvalueordefault/)(const TKey&, const TValue&) const | Возвращает значение, если найдено; иначе **defaultValue**. |
| virtual TValue [GetValueOrNull](../../system.collections.generic/idictionary/getvalueornull/)(const TKey&) const | Возвращает значение, если найдено; иначе **null**, имеет смысл только для ссылочных типов. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Конструктор по умолчанию. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)&) | Конструктор копирования. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)&&) | Конструктор перемещения. |
| virtual TValue [idx_get](../../system.collections.generic/idictionary/idx_get/)(const TKey&) const | Функция получения. |
| void [idx_set](./idx_set/)(const TKey&, TValue) override | Устанавливает элемент в указанной позиции. |
| virtual void [idx_set](../../system.collections.generic/idictionary/idx_set/)(const TKey&, TValue) | Функция установки. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)<T, T, T>&) | Применяет функцию-аккумулятор к последовательности. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function<**bool**(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет ли условию. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Преобразует элементы в указанный тип. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> ) | Конкатенирует две последовательности. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (рассчитанное прямым подсчётом). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)<T, **bool**>&) | Возвращает количество элементов в последовательности, которые удовлетворяют указанному условию. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Возвращает элемент по указанному индексу в последовательности. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Возвращает первый элемент последовательности. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)<T, **bool**>&) | Возвращает первый элемент последовательности, который удовлетворяет указанному условию. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Возвращает первый элемент последовательности или значение по умолчанию, если последовательность пуста. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function<**bool**(T)>) | Возвращает первый элемент последовательности, удовлетворяющий условию, или значение по умолчанию, если такой элемент не найден. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, T>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>) | Группирует элементы последовательности. |
| [System::SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[System::SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<T, Key>, [System::Func](../../system/func/)<T, Element>) | Группирует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Source>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<[SharedPtr](../../system/sharedptr/)<[System::Linq::IGrouping](../../system.linq/igrouping/)<Key, Element>>>> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)<Source, Key>, [System::Func](../../system/func/)<Source, Element>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Возвращает последний элемент последовательности. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Возвращает последний элемент последовательности или значение по умолчанию, если последовательность пуста. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<T, ResultType>&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<T, ResultType>&) | Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)<Source, ResultType>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Фильтрует элементы последовательности по указанному типу. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<T, Key>&) | Сортирует элементы последовательности по возрастанию в соответствии со значениями ключа, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<T>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<T, Key>&) | Сортирует элементы последовательности по убыванию в соответствии со значениями ключа, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)<Source>> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)<Source, Key>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Инвертирует порядок элементов последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, ResultType>&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<T, **int32_t**, ResultType>&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)<Source, **int32_t**, Result>&) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<T, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<ResultType>>> &) | Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)<Source, [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<Result>>> &) |  |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Возвращает указанное количество последовательных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)<T> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)<[List](../../system.collections.generic/list/)<T>> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)<[IEnumerable](../../system.collections.generic/ienumerable/)<T>> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function<**bool**(T)>) | Фильтрует последовательность по указанному предикату. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)&&) | Оператор перемещения присваивания. |
| [ICollection](../../system.collections.generic/icollection/)& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)&) | Оператор перемещения присваивания. |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | Сравнивает объекты по ссылке. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Сравнивает объекты по ссылке. |
| static std::enable_if<![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](./remove/)(const TKey&) override | Удаляет элемент из контейнера. |
| virtual **bool** [Remove](../../system.collections.generic/idictionary/remove/)(const TKey&) | Удаляет ключ из контейнера. |
| virtual **bool** [Remove](../../system.collections.generic/icollection/remove/)(const T&) | Удаляет элемент из коллекции. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| **bool** [TryAdd](./tryadd/)(const TKey&, const TValue&) | Пытается добавить пару ключ/значение в словарь. |
| virtual **bool** [TryGetValue](../../system.collections.generic/idictionary/trygetvalue/)(const TKey&, TValue&) const | Ищет значение и получает его, если найдено. |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | Возвращает реализацию begin-итератора const для текущего контейнера. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | Возвращает реализацию begin-итератора для текущего контейнера. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | Возвращает реализацию end-итератора const для текущего контейнера. |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | Возвращает реализацию end-итератора для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [ThisType](./thistype/) | Этот тип. |
| [BaseType](./basetype/) | Тип реализации. |

## Примечания

```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // Создать экземпляр класса ConcurrentDictionary.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Заполнить конкурентный словарь.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
Этот пример кода производит следующий вывод:
9
*/
```

## См. также

* Класс [Dictionary](../../system.collections.generic/dictionary/)
* Пространство имён [System::Collections::Concurrent](../)
* Библиотека [Aspose.Slides](../../)