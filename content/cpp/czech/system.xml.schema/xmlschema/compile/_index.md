---
title: Compile()
second_title: Aspose.Slides pro C++ – reference API
description: Zkompiluje XML SchemaObject Model (SOM) na informace o schématu pro validaci. Používá se k ověření syntaktické a sémantické struktury programově vytvořeného SOM. Sémantické ověřování validace se provádí během kompilace.
type: docs
weight: 352
url: /cs/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metoda


Zkompiluje XML [Schema](../../)[Object](../../../system/object/) Model (SOM) na informace o schématu pro validaci. Používá se k ověření syntaktické a sémantické struktury programově vytvořeného SOM. Sémantické ověřování validace se provádí během kompilace.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Zachytávač událostí validace, který přijímá informace o chybách validace XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metoda


Zkompiluje XML [Schema](../../)[Object](../../../system/object/) Model (SOM) na informace o schématu pro validaci. Používá se k ověření syntaktické a sémantické struktury programově vytvořeného SOM. Sémantické ověřování validace se provádí během kompilace.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Zachytávač událostí validace, který přijímá informace o chybách validace XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) používaný k rozlišení jmenných prostorů uvedených v elementech **include** a **import**. |

## Viz také

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchema](../)
* Třída [XmlResolver](../../../system.xml/xmlresolver/)
* Obor názvů [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)