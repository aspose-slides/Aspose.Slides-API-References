---
title: Compile()
second_title: Riferimento API di Aspose.Slides per C++
description: Compila il modello XML SchemaObject (SOM) in informazioni di schema per la convalida. Viene utilizzato per verificare la struttura sintattica e semantica del SOM costruito programmaticamente. La verifica della convalida semantica viene eseguita durante la compilazione.
type: docs
weight: 352
url: /it/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) method


Compila il modello XML [Schema](../../)[Object](../../../system/object/) (SOM) in informazioni di schema per la convalida. Viene utilizzato per verificare la struttura sintattica e semantica del SOM costruito programmaticamente. La verifica della convalida semantica viene eseguita durante la compilazione.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Il gestore dell'evento di convalida che riceve informazioni sugli errori di convalida XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) method


Compila il modello XML [Schema](../../)[Object](../../../system/object/) (SOM) in informazioni di schema per la convalida. Viene utilizzato per verificare la struttura sintattica e semantica del SOM costruito programmaticamente. La verifica della convalida semantica viene eseguita durante la compilazione.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Il gestore dell'evento di convalida che riceve informazioni sugli errori di convalida XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) utilizzato per risolvere gli spazi dei nomi referenziati negli elementi **include** e **import**. |

## Vedi anche

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)