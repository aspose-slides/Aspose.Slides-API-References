---
title: Transform()
second_title: Aspose.Slides для C++ справочник API
description: Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в XmlWriter.
type: docs
weight: 40
url: /ru/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) или XPathDocument, содержащий данные для преобразования. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) или XPathDocument, содержащий данные для преобразования. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в TextWriter. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) или XPathDocument, содержащий данные для преобразования. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) или XPathDocument, содержащий данные для преобразования. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в TextWriter. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI входного документа. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI входного документа. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method

Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI входного документа. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method

Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в поток. [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI входного документа. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Поток, в который вы хотите вывести результаты. |

## XslCompiledTransform::Transform(const String\&, const String\&) method

Выполняет преобразование, используя входной документ, указанный URI, и выводит результаты в файл.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI входного документа. |
| resultsFile | const [String](../../../system/string/)\& | URI выходного файла. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом [XmlReader](../../../system.xml/xmlreader/), и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения, а [XmlResolver](../../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/), содержащий входной документ. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) с пространством имён, содержащий аргументы, используемые в качестве входных данных для преобразования. Это значение может быть **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/), используемый для разрешения функции XSLT **document()**. Если это **nullptr**, функция **document()** не разрешается. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) method

Выполняет преобразование, используя входной документ, указанный объектом IXPathNavigable, и выводит результаты в [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) предоставляет дополнительные аргументы времени выполнения, а [XmlResolver](../../../system.xml/xmlresolver/) разрешает функцию XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Документ, который нужно преобразовать, указанный объектом IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Список аргументов как [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/), в который вы хотите вывести результаты. Если таблица стилей содержит элемент **xsl:output**, вам следует создать [XmlWriter](../../../system.xml/xmlwriter/) с использованием объекта [XmlWriterSettings](../../../system.xml/xmlwritersettings/), возвращённого из значения [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Это гарантирует, что у [XmlWriter](../../../system.xml/xmlwriter/) правильные настройки вывода. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/), используемый для разрешения функции XSLT **document()**. Если это **nullptr**, функция **document()** не разрешается. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)