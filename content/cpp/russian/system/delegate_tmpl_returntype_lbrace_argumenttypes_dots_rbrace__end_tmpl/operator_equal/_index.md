---
title: operator=()
second_title: Aspose.Slides для C++ Справочник API
description: 
type: docs
weight: 14
url: /ru/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_equal/
---
## Delegate< ReturnType(ArgumentTypes...)>::operator=(const Delegate\&) method




```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::operator=(Delegate\&&) method


Оператор перемещающего присваивания. Берёт на себя владение объектом, на который указывает указанный делегат.

```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(Delegate &&o) noexcept
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| o | [Delegate](../delegate/)\&& | Объект Delegate, из которого перемещается указанный объект |

### Возвращаемое значение

Ссылка на текущий объект

## См. также

* Метод [Delegate](../delegate/)
* Класс [Delegate< ReturnType(ArgumentTypes...)>](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)