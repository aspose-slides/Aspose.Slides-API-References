---
title: Compile()
second_title: Aspose.Slides for C++ API Reference
description: Compiles the XML SchemaObject Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation.
type: docs
weight: 352
url: /cpp/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Compiles the XML [Schema](../../)[Object](../../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | The validation event handler that receives information about XML [Schema](../../) validation errors. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Compiles the XML [Schema](../../)[Object](../../../system/object/) Model (SOM) into schema information for validation. Used to check the syntactic and semantic structure of the programmatically built SOM. Semantic validation checking is performed during compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | The validation event handler that receives information about the XML [Schema](../../) validation errors. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | The [XmlResolver](../../../system.xml/xmlresolver/) used to resolve namespaces referenced in **include** and **import** elements. |

## See Also

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)