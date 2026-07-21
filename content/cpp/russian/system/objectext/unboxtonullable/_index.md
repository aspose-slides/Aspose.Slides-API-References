---
title: UnboxToNullable()
second_title: Aspose.Slides для C++ справочник API
description: Разворачивает объект в тип, допускающий null.
type: docs
weight: 79
url: /ru/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable(const SmartPtr\<Object\>\&, bool) метод

Разворачивает объект в тип, допускающий null.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=1)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для развёртывания. |
| safe | **bool** | Если true, вернуть nullptr при неудаче, иначе бросить InvalidCastException. |

### Возвращаемое значение

Развёрнутый nullable-значение (может быть null).

## См. также

* Класс [Nullable](../../nullable/)
* Класс [SmartPtr](../../smartptr/)
* Класс [Object](../../object/)
* Класс [ObjectExt](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)