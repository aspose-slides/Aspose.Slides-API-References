---
title: get_SchemaInfo()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu.
type: docs
weight: 196
url: /cs/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metoda

Vrací informace o schématu, které byly přiřazeny aktuálnímu uzlu v důsledku validace schématu.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Návratová hodnota

Objekt IXmlSchemaInfo obsahující informace o schématu pro aktuální uzel. [Schema](../../../system.xml.schema/) informace mohou být nastaveny na elementy, atributy nebo na textové uzly s nenulovou [XmlReader::get_ValueType](../get_valuetype/) hodnotou. Pokud aktuální uzel není jedním z výše uvedených typů uzlů nebo pokud instance [XmlReader](../) nehlásí informace o schématu, tato metoda vrací **nullptr**. Pokud je tato metoda volána z objektu [XmlTextReader](../../xmltextreader/) nebo [XmlValidatingReader](../../xmlvalidatingreader/), tato metoda vždy vrací **nullptr**. Tyto implementace [XmlReader](../) neexponují informace o schématu prostřednictvím metody get_SchemaInfo.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)