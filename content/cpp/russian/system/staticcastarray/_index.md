---
title: StaticCastArray()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From является объектом SmartPtr obj.
type: docs
weight: 2939
url: /ru/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From является объектом [SmartPtr](../smartptr/).

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| To | Тип, к которому будут приведены элементы указанного массива |
| From | Тип элементов массива, элементы которого необходимо привести |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### Возвращаемое значение

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

Устарело
:   Добавлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) function

Выполняет приведение элементов указанного массива к другому типу. Переопределение для случаев, когда From реализует интерфейс Boxable, а To является массивом [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| To | Тип, к которому будут приведены элементы указанного массива |
| From | Тип элементов массива, элементы которого необходимо привести |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | Умный указатель на массив, содержащий элементы для приведения |

### Возвращаемое значение

Указатель на новый массив, содержащий элементы типа **To**, эквивалентные элементам **from**

Устарело
:   Добавлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Class [Object](../object/)
* Struct [IsSmartPtr](../issmartptr/)
* Struct [IsBoxable](../isboxable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)