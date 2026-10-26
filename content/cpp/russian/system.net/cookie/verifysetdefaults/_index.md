---
title: VerifySetDefaults()
second_title: Aspose.Slides для справочника API C++
description: Проверяет и задаёт значения атрибутов по умолчанию.
type: docs
weight: 482
url: /ru/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) метод


Проверяет и задаёт значения атрибутов по умолчанию.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | Спецификация cookie. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Экземпляр класса Uri, который используется для инициализации внутренних полей. |
| isLocalDomain | **bool** | Значение, указывающее, помещается ли cookie в локальный домен. |
| localDomain | [String](../../../system/string/) | Имя локального домена. |
| setDefault | **bool** | Значение, указывающее, должны ли атрибуты cookie инициализироваться с использованием значений по умолчанию. |
| shouldThrow | **bool** | Значение, указывающее, должно ли быть выброшено исключение, когда указанные значения недействительны. |

### Return Value

True, когда все значения действительны, иначе false.

## Смотрите также

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [Cookie](../)
* Пространство имён [System::Net](../../)
* Library [Aspose.Slides](../../../)