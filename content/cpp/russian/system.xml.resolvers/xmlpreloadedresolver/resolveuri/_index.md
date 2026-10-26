---
title: ResolveUri()
second_title: Справочник API Aspose.Slides для C++
description: Разрешает абсолютный URI из базовых и относительных URI.
type: docs
weight: 40
url: /ru/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) метод


Разрешает абсолютный URI из базового и относительного URI.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Базовый URI, используемый для разрешения относительного URI. |
| relativeUri | [String](../../../system/string/) | URI для разрешения. URI может быть абсолютным или относительным. Если абсолютный, это значение эффективно заменяет значение **baseUri**. Если относительный, он комбинируется с **baseUri**, образуя абсолютный URI. |

### Возвращаемое значение

[Uri](../../../system/uri/), представляющий абсолютный URI, или **nullptr**, если относительный URI нельзя разрешить.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [String](../../../system/string/)
* Класс [XmlPreloadedResolver](../)
* Пространство имён [System::Xml::Resolvers](../../)
* Библиотека [Aspose.Slides](../../../)