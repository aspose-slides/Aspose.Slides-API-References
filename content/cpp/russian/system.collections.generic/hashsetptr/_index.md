---
title: HashSetPtr
second_title: Aspose.Slides для C++ справочник API
description: Указатель для хранения ссылок HashSet. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям по значению или по константной ссылке.
type: docs
weight: 235
url: /ru/system.collections.generic/hashsetptr/
---
## HashSetPtr класс

Указатель для хранения [HashSet](../hashset/) ссылок. Этот тип является указателем для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям по значению или по константной ссылке.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Аксессор для метода [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Аксессор для метода [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к типу-наследнику с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к типу-наследнику с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Аксессор для метода [cbegin()](../../system/smartptr/cbegin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Аксессор для метода [cend()](../../system/smartptr/cend/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с помощью const_cast над объектом, на который он указывает. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с помощью dynamic_cast над объектом, на который он указывает. |
| auto [end](../../system/smartptr/end/)() | Аксессор для метода [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Аксессор для метода [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Получает указанный объект. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Получает указанный объект, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество shared-указателей, существующих для ссылочного объекта, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у указного объекта. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Получает текущий ссылочный объект (если существует) или бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Получает указанный объект (если существует) либо nullptr. То же, что [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Получает ссылочный объект. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Получает указанный объект (если существует) либо nullptr. То же, что [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | Конструктор нулевого указателя. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Конструктор копирования. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли указанный объект конкретным типом или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от собственного (созданный конструктором алиасинга). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не является nullptr. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, является ли указатель nullptr. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Получает ссылку на указанный объект. Проверяет, что указатель не nullptr. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет получить доступ к членам ссылочного объекта. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения на меньше для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения на меньше для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекту [SmartPtr](../../system/smartptr/). x становится недоступным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает необработанный указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Убирает алиасинг (созданный конструктором алиасинга) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тот же объект, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает указанный объект. |
| void [reset](../../system/smartptr/reset/)() | Перенаправляет указатель на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у ссылочного объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у указного объекта (если существует). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, или преобразует необработанный указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует копию объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует копию объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует перемещением объект [SmartPtr](../../system/smartptr/). По сути меняет местами два указателя, если они находятся в одинаковом режиме. x может стать недоступным после вызова. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# существует приведение массива, не поддерживаемое в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для преобразования некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), который разделяет информацию о владении с начальным значением ptr, но содержит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с помощью static_cast над указным объектом. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует полного определения типа Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок указного объекта и удаляет объект. |

## Смотрите также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)