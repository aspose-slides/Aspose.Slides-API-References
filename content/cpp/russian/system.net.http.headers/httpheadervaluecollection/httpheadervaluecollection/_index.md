---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides для C++ справка API
description: Создает новый экземпляр.
type: docs
weight: 40
url: /ru/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) constructor

Создает новый экземпляр.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Имя заголовка. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Коллекция HTTP заголовков. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

Создает новый экземпляр.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Имя заголовка. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Коллекция HTTP заголовков. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Делегат, используемый для проверки добавляемых элементов. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) constructor

Создает новый экземпляр.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Имя заголовка. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Коллекция HTTP заголовков. |
| specialValue | T | «специальное значение». |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) constructor

Создает новый экземпляр.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Имя заголовка. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Коллекция HTTP заголовков. |
| specialValue | T | «специальное значение». |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Делегат, используемый для проверки добавляемых элементов. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Класс [String](../../../system/string/)
* Класс [HttpHeaders](../../httpheaders/)
* Класс [HttpHeaderValueCollection](../)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)