---
title: QueuePtr
second_title: Справочник API Aspose.Slides для C++
description: Указатель на очередь. Этот тип представляет указатель, управляющий удалением другого объекта. Его следует выделять в стеке и передавать в функции по значению или по const-ссылке.
type: docs
weight: 482
url: /ru/system.collections.generic/queueptr/
---
## QueuePtr класс

[Queue](../queue/) указатель. Этот тип представляет указатель, управляемый удалением другого объекта. Его следует выделять в стеке и передавать в функции по значению или по const-ссылке.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Доступ к методу [begin()](../../system/smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к базовому типу с использованием static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к типу-наследнику с использованием dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к типу-наследнику с использованием dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Доступ к методу [cbegin()](../../system/smartptr/cbegin/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Доступ к методу [cend()](../../system/smartptr/cend/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с использованием const_cast над целевым объектом. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с использованием dynamic_cast над целевым объектом. |
| auto [end](../../system/smartptr/end/)() | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Доступ к методу [end()](../../system/smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является типом специализации с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Возвращает указанный объект. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Возвращает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Возвращает указанный объект, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество существующих shared-указателей на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у указного объекта. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Возвращает текущий объект, на который ссылается (если есть), либо бросает исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Возвращает указанный объект (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Возвращает объект, на который происходит ссылка. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Возвращает указанный объект (если есть) или nullptr. То же, что и [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли указанный объект определённого типа или его дочернего типа. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от принадлежащего (создано конструктором-алиасингом). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не равен null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Возвращает ссылку на указанный объект. Проверяет, что указатель не null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет получить доступ к членам ссылки на объект. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Предоставляет семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Предоставляет семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекту [SmartPtr](../../system/smartptr/). x становится непригодным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Назначает сырой указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
|  [QueuePtr](./queueptr/)() | Создаёт нулевой указатель. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Создаёт указатель на конкретную очередь. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Удаляет алиасинг (созданный конструктором алиасинга) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает указанный объект. |
| void [reset](../../system/smartptr/reset/)() | Переводит указатель на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у целевого объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у указного объекта (если есть). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) нулевого указателя требуемого режима. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на заданный объект, или преобразует сырой указатель в [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типа, если разрешено. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающее конструирование объекта [SmartPtr](../../system/smartptr/). По сути меняет местами два указателя, если они находятся в одинаковом режиме. x может стать непригодным после вызова. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# есть приведение массива, не поддерживаемое в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для переноса некоторых конструкций кода C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который разделяет информацию об владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с использованием static_cast над целевым объектом. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../../system/object/). Не требует полного определения типа Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок у целевого объекта и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)