---
title: StackPtr
second_title: Aspose.Slides для C++ справочника API
description: Указатель стека. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям либо по значению, либо по константной ссылке.
type: docs
weight: 612
url: /ru/system.collections.generic/stackptr/
---
## StackPtr класс

[Stack](../stack/) указатель. Этот тип является указателем для управления удалением другого объекта. Его следует выделять в стеке и передавать функциям по значению или по константной ссылке.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элемента. |

## Методы

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к типу-наследнику с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Приводит указатель к типу-наследнику с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Доступ к методу [cbegin()](../../system/smartptr/cbegin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Доступ к методу [cend()](../../system/smartptr/cend/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Приводит указатель к другому типу с помощью const_cast над объектом, на который указывает. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Приводит указатель к другому типу с помощью dynamic_cast над объектом, на который указывает. |
| auto [end](../../system/smartptr/end/)() | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Возвращает объект, на который указывает. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Возвращает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Возвращает объект, на который указывает, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество совместно используемых указателей, ссылающихся на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у объекта, на который указывает. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Возвращает текущий объект, на который ссылается (если есть), либо бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Возвращает объект, на который указывает (если есть) или nullptr. То же, что [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Возвращает объект, на который ссылается. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Возвращает объект, на который указывает (если есть) или nullptr. То же, что [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли объект, на который указывает, конкретным типом или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от принадлежащего (созданный конструктором алиасинга). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не равен null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Возвращает ссылку на объект, на который указывает. Проверяет, что указатель не null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет обращаться к членам объекта, на который ссылается. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения < (less) для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения < (less) для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающе-присваивает объект [SmartPtr](../../system/smartptr/). x становится непригодным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующе-присваивает объект [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующе-присваивает объект [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает обычный указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Убирает алиасинг (созданный конструктором алиасинга) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает объект, на который указывает. |
| void [reset](../../system/smartptr/reset/)() | Делает указатель указывающим на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у целевого объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у объекта, на который указывает (если есть). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, либо преобразует обычный указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующе-конструирует объект [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующе-конструирует объект [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающе-конструирует объект [SmartPtr](../../system/smartptr/). Фактически меняет местами два указателя, если они находятся в одинаковом режиме. x может стать непригодным после вызова. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип массивa, к которому ссылается, создавая новый массив другого типа. Полезно, если в C# есть приведение типов массивов, которое не поддерживается в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для преобразования некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который разделяет информацию о владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p. |
|  [StackPtr](./stackptr/)() | Конструирует нулевой указатель. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Конструирует указатель, ссылающийся на конкретный стек. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Приводит указатель к другому типу с помощью static_cast над объектом, на который указывает. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует, чтобы тип Pointee_ был полностью определён. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок у объекта, на который указывает, и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)