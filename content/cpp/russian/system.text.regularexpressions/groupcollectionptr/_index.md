---
title: GroupCollectionPtr
second_title: Aspose.Slides для C++: справочник API
description: Указатель на группу коллекций. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке.
type: docs
weight: 53
url: /ru/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr класс

[Group](../group/) collection pointer. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке.

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к базовому типу с использованием static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с использованием dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с использованием dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Доступ к методу [cbegin()](../../system/smartptr/cbegin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Доступ к методу [cend()](../../system/smartptr/cend/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с использованием const_cast над указываемым объектом. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с использованием dynamic_cast над указываемым объектом. |
| auto [end](../../system/smartptr/end/)() | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Получает указываемый объект. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Получает указываемый объект, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество существующих shared-указателей на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у указываемого объекта. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Получает текущий объект, на который ссылаются (если имеется), иначе бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Получает указываемый объект (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Получает объект, на который есть ссылка. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Получает указываемый объект (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
|  [GroupCollectionPtr](./groupcollectionptr/)() | Конструктор нулевого указателя. |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | Конструктор преобразования типа. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли указываемый объект конкретным типом или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличающийся от собственного (созданный через конструктор aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не равен null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Получает ссылку на указываемый объект. Проверяет, что указатель не равен null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет получать доступ к членам ссылочного объекта. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения '<' для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения '<' для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекту [SmartPtr](../../system/smartptr/). x становится недоступным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает сырой указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| [GroupPtr](../groupptr/)[operator[]](./operator[]/)(size_t) const | [Group](../group/) аксессор. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Удаляет алиасинг (созданный конструктором алиасинга) из указателя, обеспечивая, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает указываемый объект. |
| void [reset](../../system/smartptr/reset/)() | Переводит указатель на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок на объект. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у указываемого объекта (если есть). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт нулевой указатель объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, либо преобразует сырой указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт копию объекта [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт копию объекта [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. Выполняет преобразование типов, если допускается. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающее создание объекта [SmartPtr](../../system/smartptr/). По сути меняет местами два указателя, если они находятся в одном режиме. x может стать недоступным после вызова. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# есть приведение типа массива, которое не поддерживается в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для перевода некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который делит информацию о владении с исходным значением ptr, но хранит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с использованием static_cast над указываемым объектом. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует полной определения типа Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок у указываемого объекта и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Text::RegularExpressions](../)
* Библиотека [Aspose.Slides](../../)