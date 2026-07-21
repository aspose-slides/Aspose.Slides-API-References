---
title: XmlParserContext()
second_title: Справочник API Aspose.Slides для C++
description: "Создаёт новый экземпляр класса XmlParserContext с указанными XmlNameTable, XmlNamespaceManager, xml:lang и xml:space."
type: docs
weight: 261
url: /ru/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** и **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Экземпляр [XmlNameTable](../../xmlnametable/), используемый для атомизации строк. Если это **nullptr**, вместо него используется таблица имён, использованная для создания **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Область действия **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Значение XmlSpace, указывающее область действия **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** и кодировкой.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Экземпляр [XmlNameTable](../../xmlnametable/), используемый для атомизации строк. Если это **nullptr**, вместо него используется таблица имён, использованная для создания **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Область действия **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Значение XmlSpace, указывающее область действия **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Объект Encoding, указывающий параметр кодировки. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), базовым URI, **xml:lang**, **xml:space** и значениями типа документа.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Экземпляр [XmlNameTable](../../xmlnametable/), используемый для атомизации строк. Если это **nullptr**, вместо него используется таблица имён, использованная для создания **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Имя объявления типа документа. |
| pubId | const [String](../../../system/string/)\& | Общий идентификатор. |
| sysId | const [String](../../../system/string/)\& | Системный идентификатор. |
| internalSubset | const [String](../../../system/string/)\& | Внутренний набор DTD. Этот набор DTD используется для разрешения сущностей, а не для проверки документа. |
| baseURI | const [String](../../../system/string/)\& | Базовый URI для XML-фрагмента (место, из которого был загружен фрагмент). |
| xmlLang | const [String](../../../system/string/)\& | Область действия **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Значение XmlSpace, указывающее область действия **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Инициализирует новый экземпляр класса [XmlParserContext](../) с указанными [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), базовым URI, **xml:lang**, **xml:space**, кодировкой и значениями типа документа.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Экземпляр [XmlNameTable](../../xmlnametable/), используемый для атомизации строк. Если это **nullptr**, вместо него используется таблица имён, использованная для создания **nsMgr**. Для получения дополнительной информации об атомизированных строках см. [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Экземпляр [XmlNamespaceManager](../../xmlnamespacemanager/), используемый для поиска информации о пространствах имён, или **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Имя объявления типа документа. |
| pubId | const [String](../../../system/string/)\& | Общий идентификатор. |
| sysId | const [String](../../../system/string/)\& | Системный идентификатор. |
| internalSubset | const [String](../../../system/string/)\& | Внутренний набор DTD. Этот набор DTD используется для разрешения сущностей, а не для проверки документа. |
| baseURI | const [String](../../../system/string/)\& | Базовый URI для XML-фрагмента (место, из которого был загружен фрагмент). |
| xmlLang | const [String](../../../system/string/)\& | Область действия **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Значение XmlSpace, указывающее область действия **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Объект Encoding, указывающий параметр кодировки. |

## Смотрите также

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlNameTable](../../xmlnametable/)
* Класс [XmlNamespaceManager](../../xmlnamespacemanager/)
* Класс [String](../../../system/string/)
* Класс [XmlParserContext](../)
* Класс [Encoding](../../../system.text/encoding/)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)