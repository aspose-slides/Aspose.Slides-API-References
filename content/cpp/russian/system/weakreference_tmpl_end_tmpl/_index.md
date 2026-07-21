---
title: WeakReference<>
second_title: Aspose.Slides для C++ справочника API
description: Представляет слабую ссылку, которая ссылается на объект, при этом позволяя этому объекту быть удалённым.
type: docs
weight: 1496
url: /ru/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> класс

Представляет слабую ссылку, которая ссылается на объект, при этом позволяя этому объекту быть удалённым.

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | Возвращает индикатор того, удалён ли объект, на который ссылается текущий объект WeakReference. |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | Возвращает объект (цель), на который ссылается текущий объект WeakReference. |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Устанавливает объект (цель), на который ссылается текущий объект WeakReference. |
| [WeakReference](./weakreference/)() | Конструктор по умолчанию. |
| [WeakReference](./weakreference/)(std::nullptr_t) | Конструктор из nullptr. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Создаёт новый экземпляр класса WeakReference, ссылающийся на указанный объект. |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Создаёт новый экземпляр класса WeakReference, ссылающийся на указанный объект. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)