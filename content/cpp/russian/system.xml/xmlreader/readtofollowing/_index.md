---
title: ReadToFollowing()
second_title: Aspose.Slides для C++ справочник API
description: Считывает до тех пор, пока не будет найден элемент с указанным квалифицированным именем.
type: docs
weight: 898
url: /ru/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) метод

Считывает до тех пор, пока не будет найден элемент с указанным квалифицированным именем.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Квалифицированное имя элемента. |

### Return Value

**true** если найден соответствующий элемент; иначе **false** и [XmlReader](../) находится в состоянии окончания файла.

## XmlReader::ReadToFollowing(String, String) метод

Считывает до тех пор, пока не будет найден элемент с указанным локальным именем и URI пространства имён.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Локальное имя элемента. |
| namespaceURI | [String](../../../system/string/) | URI пространства имён элемента. |

### Return Value

**true** если найден соответствующий элемент; иначе **false** и [XmlReader](../) находится в состоянии окончания файла.

## See Also

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)