---
title: ResolveUri()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе определяет абсолютный URI из базового и относительного URI.
type: docs
weight: 27
url: /ru/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) метод

Когда переопределяется в производном классе, возвращает абсолютный URI, полученный из базового и относительного URI.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | [String](../../../system/string/) | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение фактически заменяет значение **baseUri**. Если относительный, он объединяется с **baseUri**, образуя абсолютный URI. |

### Возвращаемое значение

Абсолютный URI или **nullptr**, если относительный URI не может быть разрешён.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [XmlResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)