---
title: StringCollectionPtr
second_title: Справочник API Aspose.Slides для C++
description: Коллекция строк указатель с оператором доступа.
type: docs
weight: 40
url: /ru/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr класс

Коллекция строк указатель с оператором доступа.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Методы

| Method | Описание |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Метод доступа к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Метод доступа к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Метод доступа к методу [cbegin()](../../system/smartptr/cbegin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Метод доступа к методу [cend()](../../system/smartptr/cend/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с использованием const_cast над объектом, на который он указывает. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с использованием dynamic_cast над объектом, на который он указывает. |
| auto [end](../../system/smartptr/end/)() | Метод доступа к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Метод доступа к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией типа с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Возвращает объект, на который указывает указатель. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Возвращает объект, на который указывает указатель, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество существующих shared-указателей на объект, на который ссылаются, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у объекта, на который указывает указатель. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Возвращает текущий объект, на который ссылаются (если есть), иначе бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Возвращает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Возвращает объект, на который ссылаются. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Возвращает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект, на который указывает указатель, указанным типом или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от собственного (созданный конструктором aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не равен nullptr. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен nullptr. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Возвращает ссылку на объект, на который указывает указатель. Проверяет, что указатель не равен nullptr. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет получать доступ к членам объекта, на который ссылаются. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекту [SmartPtr](../../system/smartptr/). После этого x становится непригодным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает необработанный указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Функция доступа. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Удаляет aliasing (созданный конструктором aliasing) из указателя, обеспечивая, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает объект, на который указывает указатель. |
| void [reset](../../system/smartptr/reset/)() | Задает указателю значение nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счетчики ссылок у объекта, на который указывает. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у объекта, на который указывает указатель (если есть). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создает объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создает объект [SmartPtr](../../system/smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создает [SmartPtr](../../system/smartptr/), указывающий на указанный объект, или преобразует необработанный указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирует и создает объект [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирует и создает объект [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающее создание объекта [SmartPtr](../../system/smartptr/). По сути меняет местами два указателя, если они находятся в одинаковом режиме. После вызова x может стать непригодным. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, когда в C# есть приведение типа массива, которое не поддерживается в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для трансляции некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создает [SmartPtr](../../system/smartptr/), который разделяет информацию о владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с помощью static_cast над объектом, на который он указывает. |
|  [StringCollectionPtr](./stringcollectionptr/)() | Создает нулевой указатель. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Создает указатель на конкретную коллекцию. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует, чтобы тип Pointee_ был полным. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счетчик ссылок у объекта, на который указывает, и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имен [System::Collections::Specialized](../)
* Библиотека [Aspose.Slides](../../)