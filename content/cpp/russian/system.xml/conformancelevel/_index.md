---
title: ConformanceLevel
second_title: Aspose.Slides для C++ справочник API
description: Указывает степень проверки ввода или вывода, которую выполняют объекты XmlReader и XmlWriter.
type: docs
weight: 625
url: /ru/system.xml/conformancelevel/
---
## ConformanceLevel перечисление

Указывает степень проверки ввода или вывода, которую выполняют объекты [XmlReader](../xmlreader/) и [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | 0 | Объект [XmlReader](../xmlreader/) или [XmlWriter](../xmlwriter/) автоматически определяет, должна ли выполняться проверка на уровне документа или уровня фрагмента, и проводит соответствующую проверку. Если вы оборачиваете другой объект [XmlReader](../xmlreader/) или [XmlWriter](../xmlwriter/), внешний объект не выполняет дополнительной проверки соответствия. Проверка соответствия передаётся базовому объекту. |
| Fragment | 1 | XML-данные являются [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), как определено W3C. Этот уровень соответствия представляет XML-документ, который может не иметь корневого элемента, но в остальном является корректно сформированным. Такой уровень проверки гарантирует, что поток, читаемый или записываемый, может быть обработан любым процессором в качестве [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | XML-данные соответствуют правилам корректно сформированного [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed), как определено W3C. Этот уровень проверки гарантирует, что поток, читаемый или записываемый, может быть обработан любым процессором в качестве [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)