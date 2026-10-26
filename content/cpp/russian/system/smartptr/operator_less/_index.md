---
title: operator<()
second_title: Справочник API Aspose.Slides для C++
description: Обеспечивает семантику сравнения «меньше» для класса SmartPtr.
type: docs
weight: 235
url: /ru/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method


Предоставляет семантику сравнения «меньше» для класса [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Тип указателя для сравнения с текущим. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Y * | Указатель для сравнения с текущим. |

### Возвращаемое значение

True, если объект, на который ссылается [SmartPtr](../), 'less' по отношению к p, и false в противном случае.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


Предоставляет семантику сравнения «меньше» для класса [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Y | Тип указателя для сравнения с текущим. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Указатель для сравнения с текущим. |

### Возвращаемое значение

True, если объект, на который ссылается [SmartPtr](../), 'less' по отношению к x, и false в противном случае.

## См. также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)