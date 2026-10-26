---
title: ResolveUri()
second_title: Aspose.Slides для C++ справочник API
description: Получает абсолютный URI из базового и относительного URI.
type: docs
weight: 66
url: /ru/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) метод

Получает абсолютный URI из базового и относительного URI.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | [String](../../../system/string/) | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение эффективно заменяет значение **baseUri**. Если относительный, он объединяется с **baseUri**, образуя абсолютный URI. |

### Возвращаемое значение

Абсолютный URI или **nullptr**, если относительный URI нельзя разрешить.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [XmlUrlResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)