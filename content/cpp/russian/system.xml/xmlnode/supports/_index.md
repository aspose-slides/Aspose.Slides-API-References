---
title: Supports()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, реализует ли реализация DOM конкретную функцию.
type: docs
weight: 482
url: /ru/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) метод

Проверяет, реализует ли реализация DOM конкретную функцию.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Имя пакета функции для тестирования. Это имя не чувствительно к регистру. |
| version | [String](../../../system/string/) | Номер версии пакета для тестирования. Если версия не указана (null), поддержка любой версии функции приводит к тому, что метод возвращает true. |

### Return Value

**true** если функция реализована в указанной версии; в противном случае **false**.

## Remarks

В следующей таблице описаны комбинации, которые возвращают **true**. 

| Функция | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## See Also

* Класс [String](../../../system/string/)
* Класс [XmlNode](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)