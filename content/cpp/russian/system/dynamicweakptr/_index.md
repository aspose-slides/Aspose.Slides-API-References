---
title: DynamicWeakPtr
second_title: Справочник API Aspose.Slides для C++
description: Класс умного указателя, который отслеживает режимы указателей шаблонных аргументов сохраняемого объекта и обновляет их после каждого присваивания. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по const-ссылке.
type: docs
weight: 781
url: /ru/system/dynamicweakptr/
---
## DynamicWeakPtr класс

Класс умного указателя, который отслеживает режимы указателей шаблонных аргументов сохраняемого объекта и обновляет их после каждого присваивания. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать в функции либо по значению, либо по const-ссылке.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Pointee | тип. |
| trunkMode | Режим самого умного указателя, shared или weak. |
| weakLeafs | Индексы шаблонных аргументов сохраняемого типа, которые должны быть установлены в режим weak-указателя. |
## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Доступ к методу [begin()](../smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Доступ к методу [begin()](../smartptr/begin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Доступ к методу [cbegin()](../smartptr/cbegin/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Доступ к методу [cend()](../smartptr/cend/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с помощью const_cast над объектом, на который указывает указатель. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с помощью dynamic_cast над объектом, на который указывает указатель. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Создаёт нулевой умный указатель. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Создаёт умный указатель, указывающий на переданный объект. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Копирующий конструктор умного указателя. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Копирующий конструктор умного указателя. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Копирующий конструктор умного указателя. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Перемещающий конструктор умного указателя. |
| auto [end](../smartptr/end/)() | Доступ к методу [end()](../smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Доступ к методу [end()](../smartptr/end/) базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Получает объект, на который указывает указатель. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Получает объект, на который указывает указатель, но проверяет, что указатель находится в режиме shared. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Получает количество существующих shared-указателей на объект, включая текущий. Проверяет, что указатель находится в режиме shared. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../smartptr/gethashcode/) у объекта, на который указывает указатель. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Получает текущий объект (если есть) или бросает исключение. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Получает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Получает объект, на который ссылаются. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Получает объект, на который указывает указатель (если есть) или nullptr. То же, что и [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Проверяет, является ли объект, на который указывает указатель, конкретным типом или его дочерним типом. Следует семантике C# `is`. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от владеемого (созданный конструктором aliasing). |
| **bool** [IsShared](../smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Проверяет, что указатель не является нулевым. |
| **bool** [operator!](../smartptr/operator_not/)() const | Проверяет, что указатель является нулевым. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Получает ссылку на объект, на который указывает указатель. Проверяет, что указатель не нулевой. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Позволяет получить доступ к членам ссылающегося объекта. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения `less` для класса [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения `less` для класса [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Перемещающее присваивание умного указателя. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Копирующее присваивание умного указателя. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Копирующее присваивание умного указателя. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Присваивание умного указателя. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Устанавливает умный указатель в ноль. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Проверяет, что умный указатель является нулевым. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Удаляет aliasing (созданный конструктором aliasing) из указателя, гарантируя, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Устанавливает объект, на который указывает указатель. |
| void [reset](../smartptr/reset/)() | Делает указатель указывающим на nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у объекта. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у объекта, на который указывает указатель (если есть). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Создаёт объект [SmartPtr](../smartptr/) требуемого режима. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Создаёт объект [SmartPtr](../smartptr/) с нулевым указателем требуемого режима. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Создаёт [SmartPtr](../smartptr/), указывающий на заданный объект, или преобразует сырый указатель в [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Копирующий конструктор объекта [SmartPtr](../smartptr/). Оба указателя после этого указывают на один и тот же объект. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Копирующий конструктор объекта [SmartPtr](../smartptr/). Оба указателя после этого указывают на один и тот же объект. Выполняет преобразование типа, если это разрешено. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Перемещающий конструктор объекта [SmartPtr](../smartptr/). По сути меняет местами два указателя, если они находятся в одинаковом режиме. После вызова `x` может стать недоступным. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Преобразует тип массива, на который ссылаются, создавая новый массив другого типа. Полезно, когда в C# есть приведение массива, не поддерживаемое в C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для переноса некоторых конструкций кода из C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Конструирует [SmartPtr](../smartptr/), который совместно использует информацию о владении с исходным значением `ptr`, но хранит несвязанный и неуправляемый указатель `p`. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с помощью static_cast над объектом, на который указывает указатель. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Преобразует любой тип указателя в указатель на [Object](../object/). Не требует полного определения типа Pointee_. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../typeinfo/) для типа Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../smartptr/). При необходимости уменьшает счётчик ссылок у указываемого объекта и удаляет его. |
## Типы-определения

| Тип-определение | Описание |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) псевдоним базового класса. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Псевдоним типа самого себя. |
| [Pointee_](./pointee_/) | Тип указателя. |

## См. также

* Класс [SmartPtr](../smartptr/)
* Примерное имя [System](../)
* Библиотека [Aspose.Slides](../../)