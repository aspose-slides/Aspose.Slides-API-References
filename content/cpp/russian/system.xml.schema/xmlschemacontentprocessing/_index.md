---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides для справочника API C++
description: Предоставляет информацию о режиме проверки замен элементов any и anyAttribute.
type: docs
weight: 976
url: /ru/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Provides information about the validation mode of **any** and **anyAttribute** element replacements.

```cpp
enum class XmlSchemaContentProcessing
```

### Values

| Имя | Значение | Описание |
| --- | --- | --- |
| None | 0 | Элементы документа не проверяются. |
| Skip | 1 | Элементы документа должны быть корректным XML и не проверяются схемой. |
| Lax | 2 | Если соответствующая схема найдена, элементы документа будут проверяться. В противном случае ошибки не будут генерироваться. |
| Strict | 3 | Процессору схем необходимо найти схему, связанную с указанным пространством имён, чтобы проверить элементы документа. |

## См. также

* Пространство имён [System::Xml::Schema](../)
* Библиотека [Aspose.Slides](../../)