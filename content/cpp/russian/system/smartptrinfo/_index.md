---
title: SmartPtrInfo
second_title: Справочник API Aspose.Slides для C++
description: Сервисный класс для тестирования и изменения содержимого SmartPtr без знания конечного типа. Используется для сборки мусора и обнаружения циклических ссылок и т.д. Представьте его как «указатель на указатель». Мы не можем использовать базовый тип SmartPtr, поскольку его нет; вместо этого используем этот класс «info».
type: docs
weight: 1223
url: /ru/system/smartptrinfo/
---
## Класс SmartPtrInfo


Сервисный класс для проверки и изменения содержимого [SmartPtr](../smartptr/) без знания конечного типа. Используется для сборки мусора и обнаружения циклических ссылок и т. д. Представьте его как 'pointer to pointer'. Мы не можем использовать базовый тип [SmartPtr](../smartptr/), так как его нет; вместо этого мы используем этот класс 'info'.

```cpp
class SmartPtrInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | Получает указатель на необработанный объект, на который указывает ссылочный указатель. |
| [Object](../object/) * [getObject](./getobject/)() const | Получает объект, на который указывает ссылочный указатель. |
| [Object](../object/) * [getOwned](./getowned/)() const | Получает указатель на объект, принадлежащий. |
| [operator bool](./operator_bool/)() const | Проверяет, указывает ли объект info на ненулевой указатель. |
| **bool** [operator!](./operator_not/)() const | Проверяет, не указывает ли объект info на ненулевой указатель. |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | Позволяет вызывать методы [Object](../object/), на которые указывает ссылочный указатель. |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | Сравнивает значения указателей, на которые ссылаются два объекта info, используя оператор <. |
| [SmartPtrInfo](./smartptrinfo/)() | Создаёт пустой объект [SmartPtrInfo](./). |
| explicit [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | Создаёт объект [SmartPtrInfo](./) с информацией о конкретном умном указателе. |

## Смотрите также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)