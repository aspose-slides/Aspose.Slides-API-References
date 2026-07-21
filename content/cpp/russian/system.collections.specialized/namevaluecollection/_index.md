---
title: NameValueCollection
second_title: Справочник API Aspose.Slides для C++
description: Коллекция связанных строковых ключей и строковых значений, к которым можно обращаться как по ключу, так и по индексу.
type: docs
weight: 14
url: /ru/system.collections.specialized/namevaluecollection/
---
## NameValueCollection класс

Коллекция связанных [String](../../system/string/) ключей и [String](../../system/string/) значений, к которым можно обратиться либо по ключу, либо по индексу.

```cpp
class NameValueCollection : public System::Collections::Generic::ICollection<System::String>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Add](./add/)(const [String](../../system/string/)\&) override | Переопределяет метод [ICollection](../../system.collections/icollection/) — не реализовано. |
| void [Add](./add/)(const [System::SharedPtr](../../system/sharedptr/)\<[NameValueCollection](./)\>\&) | Копирует записи из указанного [NameValueCollection](./) в текущий. |
| virtual void [Add](./add/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Добавляет запись с указанным именем и значением. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | Возвращает итератор, указывающий на первый элемент (если есть) коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, потому что [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает копию объекта типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | Возвращает итератор, указывающий на первый элемент (если есть) константного экземпляра коллекции. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | Возвращает итератор, указывающий на первый элемент, помеченный как const (если есть), в коллекции. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | Возвращает итератор, указывающий сразу после последнего const-элемента (если есть) в коллекции. |
| void [Clear](./clear/)() override | Удаляет все элементы. |
| **bool** [Contains](./contains/)(const [String](../../system/string/)\&) const override | Проверяет, присутствует ли элемент в коллекции. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, **int32_t**) override | Копирует элементы коллекции в существующие элементы массива. |
| virtual void [CopyTo](../../system.collections.generic/icollection/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) | Копирует все элементы коллекции в существующие элементы массива. |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | Возвращает итератор, указывающий сразу после последнего элемента (если есть) в коллекции. Этот итератор нельзя использовать для изменения ссылочного объекта, поскольку [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) возвращает копию объекта типа T. |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | Возвращает итератор, указывающий сразу после последнего элемента (если есть) константного экземпляра коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение вещественных чисел в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел двойной точности в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [String](../../system/string/) [Get](./get/)(const [String](../../system/string/)\&) | Возвращает значения, связанные с указанным ключом. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_AllKeys](./get_allkeys/)() | Возвращает все ключи. |
| int [get_Count](./get_count/)() const override | Возвращает количество пар ключ/значение. |
| virtual **bool** [get_IsReadOnly](../../system.collections.generic/icollection/get_isreadonly/)() const | Проверяет, является ли коллекция только для чтения. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[String](../../system/string/)\>\> [get_Keys](./get_keys/)() | Возвращает все ключи. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Возвращает объект, через который синхронизируется коллекция. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[String](../../system/string/)\>\> [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель для перебора элементов коллекции. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetValues](./getvalues/)(const [String](../../system/string/)\&) | Возвращает значения, связанные с указанным ключом. |
| **bool** [HasKeys](./haskeys/)() | Возвращает значение, указывающее, содержит ли [NameValueCollection](./) ключи, не равные null. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Конструктор по умолчанию. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Конструктор копирования. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Конструктор перемещения. |
| [String](../../system/string/) [idx_get](./idx_get/)(const [String](../../system/string/)\&) | Возвращает значение по указанному индексу. |
| void [idx_set](./idx_set/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Устанавливает значение записи. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Применяет функцию-аккумулятор к последовательности. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Определяет, удовлетворяют ли все элементы последовательности условию. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Определяет, содержит ли последовательность какие-либо элементы. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Определяет, существует ли любой элемент последовательности или удовлетворяет ли он условию. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Преобразует элементы к указанному типу. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Объединяет две последовательности. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Определяет, содержит ли последовательность указанное значение. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Возвращает количество элементов в последовательности (вычисленное прямым подсчётом). |
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
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по возрастанию в соответствии со значениями ключей, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Сортирует элементы последовательности по убыванию в соответствии со значениями ключей, выбранными keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Инвертирует порядок элементов в последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Преобразует элементы последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Проецирует каждый элемент последовательности и объединяет получившиеся последовательности в одну. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Возвращает указанное количество последовательных элементов с начала последовательности. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Создаёт массив из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Создаёт List<T> из последовательности. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Фильтрует последовательность согласно указанному предикату. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [NameValueCollection](./namevaluecollection/)() | Инициализирует новый пустой экземпляр класса [NameValueCollection](./). |
| [NameValueCollection](./namevaluecollection/)(const [System::SharedPtr](../../system/sharedptr/)\<[NameValueCollection](./)\>\&) | Копирует записи из указанного [NameValueCollection](./) в новый [NameValueCollection](./). |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Оператор перемещения присваивания. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Оператор перемещения присваивания. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](./remove/)(const [String](../../system/string/)\&) override | Удаляет конкретный элемент. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [Set](./set/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Устанавливает значение записи. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в weak-указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать непосредственно; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать непосредственно; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Возвращает реализацию begin const-итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Возвращает реализацию begin-итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Возвращает реализацию end const-итератора для текущего контейнера. |
| System::Details::VirtualizedIteratorBase\<[System::String](../../system/string/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Возвращает реализацию end-итератора для текущего контейнера. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать непосредственно; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать непосредственно; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ICollection](../../system.collections.generic/icollection/)
* Пространство имён [System::Collections::Specialized](../)
* Библиотека [Aspose.Slides](../../)