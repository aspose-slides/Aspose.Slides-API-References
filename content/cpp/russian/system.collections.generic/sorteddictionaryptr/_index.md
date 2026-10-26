---
title: SortedDictionaryPtr
second_title: Aspose.Slides для C++ справочник API
description: Указатель на отсортированный словарь с операторами доступа. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции по значению или по константной ссылке.
type: docs
weight: 534
url: /ru/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr класс

Sorted dictionary pointer with access operators. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<SortedDictionary<T, V>>
```

## Методы

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Метод доступа к [begin()](../../system/smartptr/begin/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [begin()](../../system/smartptr/begin/) методом. |
| auto [begin](../../system/smartptr/begin/)() const | Метод доступа к [begin()](../../system/smartptr/begin/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [begin()](../../system/smartptr/begin/) методом. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к типу-производному с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к типу-производному с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Метод доступа к [cbegin()](../../system/smartptr/cbegin/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [cbegin()](../../system/smartptr/cbegin/) методом. |
| auto [cend](../../system/smartptr/cend/)() const | Метод доступа к [cend()](../../system/smartptr/cend/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [cend()](../../system/smartptr/cend/) методом. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Приводит указатель к другому типу с помощью const_cast к объекту, на который указывает указатель. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Приводит указатель к другому типу с помощью dynamic_cast к объекту, на который указывает указатель. |
| auto [end](../../system/smartptr/end/)() | Метод доступа к [end()](../../system/smartptr/end/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [end()](../../system/smartptr/end/) методом. |
| auto [end](../../system/smartptr/end/)() const | Метод доступа к [end()](../../system/smartptr/end/) методу базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с [end()](../../system/smartptr/end/) методом. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Возвращает объект, на который указывает указатель. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Возвращает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Возвращает объект, на который указывает указатель, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество существующих shared-указателей на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у объекта, на который указывает указатель. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Возвращает текущий объект (если он существует) или бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Возвращает объект, на который указывает указатель (если он существует) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Возвращает объект, на который указывает указатель. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Возвращает объект, на который указывает указатель (если он существует) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект, на который указывает указатель, конкретным типом или его дочерним типом. Соответствует семантике C# ‘is’. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличающийся от владельца (созданный конструктором aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, не является ли указатель нулевым. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, является ли указатель нулевым. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Возвращает ссылку на объект, на который указывает указатель. Проверяет, что указатель не нулевой. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет обращаться к членам объекта, на который указывает указатель. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Предоставляет семантику сравнения «меньше» для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Предоставляет семантику сравнения «меньше» для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекта [SmartPtr](../../system/smartptr/). x становится недоступным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекта [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекта [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает необработанный указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| V\& [operator[]](./operator[]/)(const T\&) const | Функция-доступа. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Удаляет aliasing (созданный конструктором aliasing) из указателя, обеспечивая, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает объект, на который указывает указатель. |
| void [reset](../../system/smartptr/reset/)() | Делает указатель указывающим на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у ссылочного объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у объекта, на который указывает указатель (если он существует). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, либо преобразует необработанный указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающее конструирование объекта [SmartPtr](../../system/smartptr/). По сути меняет местами два указателя, если они находятся в одинаковом режиме. x может стать недоступным после вызова. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип массива, на который ссылаются, создавая новый массив другого типа. Полезно, когда в C# существует приведение массива, не поддерживаемое в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для преобразования некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который разделяет информацию о владении с исходным значением ptr, но хранит несвязанный и неуправляемый указатель p. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)() | Конструирует нулевой указатель. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedDictionary](../sorteddictionary/)\<T, V\>\>\&) | Конструирует указатель на указанный отсортированный словарь. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Приводит указатель к другому типу с помощью static_cast к объекту, на который указывает указатель. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует, чтобы тип Pointee_ был полностью определён. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Ярлык для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок у объекта, на который указывает указатель, и удаляет объект. |
## См. также

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)