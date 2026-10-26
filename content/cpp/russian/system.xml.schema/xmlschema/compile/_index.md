---
title: Compile()
second_title: Aspose.Slides для C++ API справка
description: Компилирует XML SchemaObject Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка валидности выполняется во время компиляции.
type: docs
weight: 352
url: /ru/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) метод

Компилирует XML [Schema](../../)[Object](../../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка валидности выполняется во время компиляции.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Обработчик событий проверки, получающий информацию об ошибках проверки XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) метод

Компилирует XML [Schema](../../)[Object](../../../system/object/) Model (SOM) в информацию схемы для проверки. Используется для проверки синтаксической и семантической структуры программно построенного SOM. Семантическая проверка валидности выполняется во время компиляции.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Обработчик событий проверки, получающий информацию об ошибках проверки XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения пространств имён, указанных в **include** и **import** элементах. |

## См. также

* Типовое определение [ValidationEventHandler](../../validationeventhandler/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../)
* Класс [XmlResolver](../../../system.xml/xmlresolver/)
* Пространство имён [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)