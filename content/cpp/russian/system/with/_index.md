---
title: With()
second_title: Справочник API Aspose.Slides для C++
description: Клонирует запись ссылки и применяет к ней инициализирующий функтор.
type: docs
weight: 2575
url: /ru/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) функция


Клонирует запись ссылки и применяет к ней инициализирующий функтор.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип записи для клонирования. |
| A | Тип инициализирующего функтора. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Умный указатель на объект, который необходимо клонировать и инициализировать. |
| initializer | const A\& | Инициализирующий функтор, применяемый к клону записи. |

### Возвращаемое значение

Умный указатель на клонированную запись.

## System::With(const T\&, const A\&) функция


Копирует структуру записи и применяет к ней инициализирующий функтор.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип записи для копирования. |
| A | Тип инициализирующего функтора. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| record | const T\& | Запись для копирования и инициализации. |
| initializer | const A\& | Инициализирующий функтор, применяемый к копии записи. |

### Возвращаемое значение

Скопированная запись.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)