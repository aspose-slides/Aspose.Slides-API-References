---
title: WeakPtr
second_title: "Справочник API Aspose.Slides для C++"
description: "Подкласс System::SmartPtr, который при создании переводит себя в режим weak. Обратите внимание, что этот класс не гарантирует, что его экземпляр всегда останется в режиме weak, поскольку set_Mode() всё ещё доступен. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции по значению или по константной ссылке."
type: docs
weight: 1470
url: /ru/system/weakptr/
---
## Класс WeakPtr

Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта, на который указывает указатель. |

## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Доступ к методу [begin()](../smartptr/begin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Доступ к методу [begin()](../smartptr/begin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Доступ к методу [cbegin()](../smartptr/cbegin/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Доступ к методу [cend()](../smartptr/cend/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с помощью const_cast на объекте, на который он указывает. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с помощью dynamic_cast на объекте, на который он указывает. |
| auto [end](../smartptr/end/)() | Доступ к методу [end()](../smartptr/end/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Доступ к методу [end()](../smartptr/end/) базовой коллекции. Компилируется только если тип специализации SmartPtr_ имеет метод [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Проверяет, был ли удалён объект, на который ссылается указатель. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Возвращает объект, на который указывает указатель. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Возвращает объект, на который указывает указатель, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Возвращает количество shared-указателей, указывающих на объект, включая текущий. Проверяет, что текущий указатель находится в режиме shared. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Возвращает объект, на который ссылается указатель. Проверяет, что указатель находится в режиме weak. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../smartptr/gethashcode/) у объекта, на который указывает указатель. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Возвращает текущий объект, на который ссылается (если существует), иначе бросает исключение. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Возвращает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Возвращает объект, на который ссылается указатель. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Возвращает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Проверяет, является ли объект, на который указывает указатель, экземпляром указанного типа или его наследником. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличающийся от собственного (созданный конструктором aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Проверяет, что указатель не равен null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Проверяет, является ли указатель null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Возвращает ссылку на объект, на который указывает указатель. Проверяет, что указатель не null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Позволяет обращаться к членам объекта, на который ссылается указатель. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Предоставляет семантику сравнения less для класса [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Предоставляет семантику сравнения less для класса [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Присваивает значение weak-указателю. Вызывает конкретный оператор присваивания SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Перемещающее присваивание объекта [SmartPtr](../smartptr/). x становится неиспользуемым. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Копирующее присваивание объекта [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Копирующее присваивание объекта [SmartPtr](../smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Присваивает сырой указатель объекту [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Проверяет, является ли weak-указатель null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Удаляет aliasing (созданный конструктором aliasing) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тот же объект, на который указывает. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Устанавливает объект, на который указывает указатель. |
| void [reset](../smartptr/reset/)() | Переводит указатель на nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у объекта. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у объекта, на который указывает (если существует). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Создаёт объект [SmartPtr](../smartptr/) требуемого режима. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Создаёт объект [SmartPtr](../smartptr/) с null-указателем требуемого режима. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Создаёт [SmartPtr](../smartptr/), указывающий на указанный объект, либо преобразует сырой указатель в [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Копирует объект [SmartPtr](../smartptr/). Оба указателя будут указывать на один и тот же объект. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Копирует объект [SmartPtr](../smartptr/). Оба указателя будут указывать на один и тот же объект. Выполняет преобразование типов, если разрешено. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Перемещающее конструирование объекта [SmartPtr](../smartptr/). Эффективно меняет два указателя местами, если они одного режима. x может стать неиспользуемым после вызова. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Преобразует тип массива, на который ссылается, создавая новый массив другого типа. Полезно, когда в C# есть приведение массива, не поддерживаемое в C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для трансляции некоторых конструкций кода C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Создаёт [SmartPtr](../smartptr/), который делит информацию о владении с исходным значением ptr, но хранит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с помощью static_cast на объекте, на который он указывает. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../object/). Не требует полного определения типа Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Сокращённый способ получения объекта [System::TypeInfo](../typeinfo/) для типа Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Создаёт null-указатель. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Создаёт weak-указатель для данного объекта. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Создаёт weak-указатель, ссылающийся на тот же объект, что и ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Создаёт weak-указатель, ссылающийся на тот же объект, что и x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Копирующее конструирование weak-указателя. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Копирующее конструирование weak-указателя. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Перемещающее конструирование weak-указателя. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../smartptr/). При необходимости уменьшает счётчик ссылок у объекта и удаляет его. |

## Типы-определения

| Тип | Описание |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Псевдоним для соответствующего класса [SmartPtr](../smartptr/). |
| [WeakPtr_](./weakptr_/) | Псевдоним для собственного типа. |
| [Pointee_](./pointee_/) | Тип, на который указывает указатель. |

## См. также

* Класс [SmartPtr](../smartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)