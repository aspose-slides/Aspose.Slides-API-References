---
title: ResolveUri()
second_title: Справочник API Aspose.Slides для C++
description: Разрешает абсолютный URI из базового и относительного URI, вызывая ResolveUri у базового XmlResolver.
type: docs
weight: 40
url: /ru/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) метод

Разрешает абсолютный URI из базового и относительного URI, вызывая **ResolveUri** у базового [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | [String](../../../system/string/) | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение эффективно заменяет значение **baseUri**. Если относительный, оно комбинируется с **baseUri**, образуя абсолютный URI. |

### Возвращаемое значение

Абсолютный URI или **nullptr**, если относительный URI невозможно разрешить (возвращается вызовом **ResolveUri** у базового [XmlResolver](../../xmlresolver/)).

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [XmlSecureResolver](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)