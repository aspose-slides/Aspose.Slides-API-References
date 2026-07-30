---
title: ToString()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il valore stringa di XmlQualifiedName.
type: docs
weight: 79
url: /it/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metodo


Restituisce il valore stringa di [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Valore di ritorno

Il valore stringa di [XmlQualifiedName](../) nel formato **namespace:localname**. Se l'oggetto non ha un namespace definito, questo metodo restituisce solo il nome locale.

## XmlQualifiedName::ToString(const String\&, const String\&) metodo


Restituisce il valore stringa di [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome dell'oggetto. |
| ns | const [String](../../../system/string/)\& | Il namespace dell'oggetto. |

### Valore di ritorno

Il valore stringa di [XmlQualifiedName](../) nel formato **namespace:localname**. Se l'oggetto non ha un namespace definito, questo metodo restituisce solo il nome locale.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlQualifiedName](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)