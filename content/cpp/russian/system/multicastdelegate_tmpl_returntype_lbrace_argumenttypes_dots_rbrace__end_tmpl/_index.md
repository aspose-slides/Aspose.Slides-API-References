---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Справочник API Aspose.Slides для C++
description: "Представляет коллекцию делегатов. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1080
url: /ru/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> класс


Represents a collection of delegates. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| ReturnType | Return type of the invokable entities pointed to by each delegate in the collection |
| ArgumentTypes | Argument list of the invokable entities pointed to by each delegate in the collection |
## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | НЕ РЕАЛИЗОВАНО. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Добавляет указанный делегат в коллекцию. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Добавляет указанный объект функции в коллекцию делегатов. Объект функции преобразуется в тип делегата Callback перед добавлением в коллекцию. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Добавляет указанный объект MulticastDelegate в коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Добавляет указанный нестатический метод указанного объекта в коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Удаляет указанный делегат из коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Удаляет указанный нестатический метод указанного объекта из коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Удаляет указанный нестатический метод указанного объекта из коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Удаляет указанный объект MulticastDelegate из коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Удаляет все делегаты из коллекции делегатов. |
| **bool** [empty](./empty/)() const | Определяет, пуста ли коллекция делегатов. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | НЕ РЕАЛИЗОВАНО. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Вызывает все делегаты, присутствующие в данный момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Метод блокируется, пока делегаты выполняются. |
| **bool** [IsNull](./isnull/)() const | Определяет, пуста ли коллекция делегатов. |
|  [MulticastDelegate](./multicastdelegate/)() | Создаёт пустую коллекцию. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Эквивалентно конструктору по умолчанию. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Выполняет поверхностное копирование коллекции делегатов. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Конструктор перемещения. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Создаёт экземпляр и помещает указанный делегат в коллекцию делегатов. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Создаёт экземпляр и помещает указанное значение в коллекцию делегатов. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Создаёт экземпляр и помещает указанное значение в коллекцию делегатов. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Определяет, не пуста ли коллекция делегатов. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Определяет, не равны ли два экземпляра MulticastDelegate — текущий объект и указанный объект. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Вызывает все делегаты, присутствующие в данный момент в коллекции делегатов. Делегаты вызываются в том же порядке, в котором они были добавлены в коллекцию. Оператор блокируется, пока делегаты выполняются. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Добавляет указанный делегат в коллекцию. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Удаляет указанный делегат из коллекции делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Назначает коллекцию делегатов, представленную указанным объектом, текущему объекту. В результате оба объекта указывают на одну и ту же коллекцию делегатов. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Оператор присваивания перемещением. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Определяет, пуста ли коллекция делегатов. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Определяет, равны ли два экземпляра MulticastDelegate — текущий объект и указанный объект. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Очищает содержащиеся пустые обратные вызовы (на самом деле ничего не вызывая). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Возвращает ссылку на объект [TypeInfo](../typeinfo/), представляющий информацию о типе класса MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Деструктор. |
## typedef

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | Тип делегатов, представляемых классом MulticastDelegate. |
| [Function](./function/) | Тип функции, связанной с сигнатурой делегата. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)