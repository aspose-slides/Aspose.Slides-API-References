---
title: DictionaryPtr
second_title: Aspose.Slides для C++ справочник API
description: Класс указателя словаря с перегрузкой операторов. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям по значению или по константной ссылке.
type: docs
weight: 170
url: /ru/system.collections.generic/dictionaryptr/
---
## DictionaryPtr класс

[Dictionary](../dictionary/) класс указателя с перегрузкой операторов. Этот тип представляет собой указатель для управления удалением другого объекта. Его следует размещать в стеке и передавать функциям по значению или по константной ссылке.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип ключа. |
| V | Тип значения. |
## Методы

| Метод | Описание |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Метод доступа к [begin()](../../system/smartptr/begin/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Метод доступа к [begin()](../../system/smartptr/begin/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к его собственному типу. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к базовому типу с помощью static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Преобразует указатель к производному типу с помощью dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Метод доступа к [cbegin()](../../system/smartptr/cbegin/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Метод доступа к [cend()](../../system/smartptr/cend/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Преобразует указатель к другому типу с помощью const_cast на целевом объекте. |
| [DictionaryPtr](./dictionaryptr/)() | Инициализирует нулевой указатель. |
| [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | Преобразует тип указателя. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Преобразует указатель к другому типу с помощью dynamic_cast на целевом объекте. |
| auto [end](../../system/smartptr/end/)() | Метод доступа к [end()](../../system/smartptr/end/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Метод доступа к [end()](../../system/smartptr/end/) в базовой коллекции. Компилируется только если SmartPtr_ является специализацией с методом [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Получает указанный объект. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Получает режим указателя. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Получает указанный объект, при этом проверяется, что указатель находится в режиме shared. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Возвращает количество существующих shared-указателей на объект, включая текущий. Проверяется, что текущий указатель находится в режиме shared. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Вызывает [GetHashCode()](../../system/smartptr/gethashcode/) у целевого объекта. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Получает текущий объект, на который ссылаются (если есть), иначе генерирует исключение. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Получает объект, на который указывает (если есть) или nullptr. То же, что [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Получает объект, на который есть ссылка. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Получает объект, на который указывает (если есть) или nullptr. То же, что [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Проверяет, является ли целевой объект указанного типа или его дочерним типом. Соответствует семантике C# 'is'. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Проверяет, указывает ли указатель на объект, отличный от собственного (созданный конструктором aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Проверяет, находится ли указатель в режиме shared. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Проверяет, находится ли указатель в режиме weak. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Проверяет, что указатель не null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Проверяет, что указатель равен null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Получает ссылку на указанный объект. Проверяется, что указатель не null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Позволяет обращаться к членам объекта, на который есть ссылка. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Обеспечивает семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Обеспечивает семантику сравнения < для класса [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Перемещающее присваивание объекту [SmartPtr](../../system/smartptr/). После операции x становится недоступным. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Копирующее присваивание объекту [SmartPtr](../../system/smartptr/). Выполняет необходимые преобразования типов. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Присваивает сырой указатель объекту [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Устанавливает значение указателя в nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Проверяет, указывает ли указатель на nullptr. |
| V\& [operator[]](./operator[]/)(const X\&) const | Оператор доступа для работы с преобразованием типа ключа. |
| V\& [operator[]](./operator[]/)(const T\&) const | Оператор доступа. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Удаляет aliasing (созданный конструктором aliasing) из указателя, обеспечивая, что он управляет (если shared) или отслеживает (если weak) тем же объектом, на который указывает. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Устанавливает указанный объект. |
| void [reset](../../system/smartptr/reset/)() | Переключает указатель на nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Устанавливает режим указателя. Может изменить счётчики ссылок у целевого объекта. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Вызывает метод SetTemplateWeakPtr() у целевого объекта (если он существует). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) в требуемом режиме. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт объект [SmartPtr](../../system/smartptr/) с нулевым указателем в требуемом режиме. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Создаёт [SmartPtr](../../system/smartptr/), указывающий на указанный объект, либо преобразует сырой указатель в [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Копирующее конструирование объекта [SmartPtr](../../system/smartptr/). После этого оба указателя указывают на один и тот же объект. Выполняет преобразование типов, если разрешено. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Перемещающее конструирование объекта [SmartPtr](../../system/smartptr/). По сути, меняет местами два указателя, если они находятся в одинаковом режиме. После вызова x может стать недоступным. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Преобразует тип массива ссылок, создавая новый массив другого типа. Полезно, когда в C# существует приведение массива, которое не поддерживается в C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Инициализирует пустой массив. Используется для перевода некоторых конструкций кода C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Конструирует [SmartPtr](../../system/smartptr/), который разделяет информацию о владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Преобразует указатель к другому типу с помощью static_cast на целевом объекте. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Преобразует любой тип указателя к указателю на [Object](../../system/object/). Не требует полного определения типа Pointee_. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Сокращение для получения объекта [System::TypeInfo](../../system/typeinfo/) для типа Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Уничтожает объект [SmartPtr](../../system/smartptr/). При необходимости уменьшает счётчик ссылок целевого объекта и удаляет объект. |

## См. также

* Класс [SmartPtr](../../system/smartptr/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)