---
title: SmartPtr()
second_title: Справочник API Aspose.Slides для C++
description: Создает объект SmartPtr требуемого режима.
type: docs
weight: 1
url: /ru/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) constructor


Создает объект [SmartPtr](../) требуемого режима.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) constructor


Создает объект [SmartPtr](../) нулевого указателя требуемого режима.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | Режим указателя. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) constructor


Создает [SmartPtr](../) указывающий на указанный объект, или преобразует сырой указатель в [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Указатель. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(const SmartPtr_\&, SmartPtrMode) constructor


Создает копию объекта [SmartPtr](../). Оба указателя указывают на один и тот же объект после этого.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Указатель для копирования. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) constructor


Создает копию объекта [SmartPtr](../). Оба указателя указывают на один и тот же объект после этого. Выполняет преобразование типа, если это разрешено.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Q | Тип объекта, на который указывает x. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Указатель для копирования. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(SmartPtr_\&&, SmartPtrMode) constructor


Создает объект [SmartPtr](../) перемещения. По сути меняет местами два указателя, если они оба одного режима. После вызова x может стать недоступным.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Указатель для перемещения. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) constructor


Преобразует тип ссылочного массива, создавая новый массив другого типа. Полезно, если в C# есть приведение типа массива, которое не поддерживается в C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Тип исходного массива. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Указатель на массив, копию которого нужно создать, но с элементами другого типа. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |

## SmartPtr::SmartPtr(const Y\&) constructor


Инициализирует пустой массив. Используется для преобразования некоторых конструкций кода C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | Заполнитель типа EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) constructor


Создает [SmartPtr](../), который делит информацию о владении с исходным значением ptr, но содержит несвязанный и неуправляемый указатель p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Другой умный указатель, от которого будет разделено владение. |
| p | [Pointee_](../pointee_/) * | Указатель на объект для управления. |
| mode | [SmartPtrMode](../../smartptrmode/) | Режим указателя. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Этот класс содержит поле, которое будет выведено.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Этот класс содержит экземпляр класса Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Используется для вывода строки из экземпляра класса Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Выводит количество разделяемых указателей, указывающих на объект.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Создаёт SharedPtr на экземпляр класса Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Создаёт SharedPtr, который будет указывать на поле экземпляра класса Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Делает указатель 'bar' указывающим на nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data всё ещё существует, а указатель 'foo' валиден.
  PrintMessage(foo);

  return 0;
}
/*
Этот пример кода выводит следующее:
Количество разделяемых указателей: 1
Количество разделяемых указателей: 2
Количество разделяемых указателей: 0
Привет, мир!
*/
``` |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)