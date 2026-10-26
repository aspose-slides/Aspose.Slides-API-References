---
title: SortedSetPtr
second_title: Aspose.Slides для C++ справочник API
description: Указатель для удержания ссылок SortedSet. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке.
type: docs
weight: 586
url: /ru/system.collections.generic/sortedsetptr/
---
## SortedSetPtr класс

Указатель для удержания [SortedSet](../sortedset/) ссылок. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## Методы

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Метод доступа к [begin()](../../system/smartptr/begin/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Метод доступа к [begin()](../../system/smartptr/begin/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к базовому типу с использованием static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к производному типу с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к производному типу с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Метод доступа к [cbegin()](../../system/smartptr/cbegin/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Метод доступа к [cend()](../../system/smartptr/cend/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Приводит указатель к другому типу с использованием const_cast к объекту. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Приводит указатель к другому типу с помощью dynamic_cast к объекту. |
| auto [end](../../system/smartptr/end/)() | Метод доступа к [end()](../../system/smartptr/end/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Метод доступа к [end()](../../system/smartptr/end/) методу базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Получает объект, на который указывает указатель. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Получает объект, на который указывает указатель, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество shared-указателей, ссылающихся на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у объекта. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Получает текущий объект, на который ссылается (если есть), либо бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Получает объект, на который указывает указатель (если есть) или nullptr. Аналогично [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Получает объект, на который ссылается указатель. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Получает объект, на который указывает указатель (если есть) или nullptr. Аналогично [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект, на который указывает указатель, определённым типом или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от собственного (созданный конструктором aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не равен null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Получает ссылку на объект, на который указывает указатель. Проверяет, что указатель не null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет обращаться к членам объекта, на который ссылается указатель. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения '<' для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения '<' для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающе-присваивает объект [SmartPtr](../../system/smartptr/). x становится недоступным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующе-присваивает объект [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующе-присваивает объект [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает необработанный указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Убирает aliasing (созданный конструктором aliasing) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает объект, на который указывает указатель. |
| void [reset](../../system/smartptr/reset/)() | Переводит указатель на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у указуемого объекта (если есть). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, либо преобразует необработанный указатель к [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирует объект [SmartPtr](../../system/smartptr/). После этого оба указателя ссылаются на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирует объект [SmartPtr](../../system/smartptr/). После этого оба указателя ссылаются на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающе-конструирует объект [SmartPtr](../../system/smartptr/). По сути, меняет местами два указателя, если они в одинаковом режиме. После вызова x может стать недоступным. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип массива, на который ссылается, создавая новый массив другого типа. Полезно, когда в C# есть приведение типов массивов, которое не поддерживается в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется при трансляции некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который делит информацию о владении с исходным значением ptr, но хранит несвязанный и неуправляемый указатель p. |
|  [SortedSetPtr](./sortedsetptr/)() | Конструктор нулевого указателя. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | Конструктор копии. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Приводит указатель к другому типу с помощью static_cast к объекту. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует полной информации о типе Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок у указываемого объекта и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)