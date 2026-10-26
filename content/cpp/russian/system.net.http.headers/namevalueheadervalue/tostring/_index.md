---
title: ToString()
second_title: Справочник API Aspose.Slides для C++
description: Аналог метода C# Object.ToString(). Позволяет преобразовывать пользовательские объекты в строку.
type: docs
weight: 79
url: /ru/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const метод

Аналог метода C# [Object.ToString()](../../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Возвращаемое значение

[String](../../../system/string/) представление, предоставляемое конечным классом.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) метод


Возвращает строковое представление коллекции экземпляров NameValueHeaderValue-class.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Коллекция экземпляров NameValueHeaderValue-class. |
| separator | char16_t | Строковый разделитель. |
| leadingSeparator | **bool** | Значение, указывающее, следует ли добавлять строковый разделитель перед первым элементом коллекции. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Экземпляр, в который будет записано строковое представление. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) метод


Возвращает строковое представление коллекции экземпляров NameValueHeaderValue-class.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Коллекция экземпляров NameValueHeaderValue-class. |
| separator | char16_t | Строковый разделитель. |
| leadingSeparator | **bool** | Значение, указывающее, следует ли добавлять строковый разделитель перед первым элементом коллекции. |

### Возвращаемое значение

Строковое представление коллекции экземпляров NameValueHeaderValue-class.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [NameValueHeaderValue](../)
* Класс [ObjectCollection](../../objectcollection/)
* Класс [StringBuilder](../../../system.text/stringbuilder/)
* Пространство имён [System::Net::Http::Headers](../../)
* Библиотека [Aspose.Slides](../../../)