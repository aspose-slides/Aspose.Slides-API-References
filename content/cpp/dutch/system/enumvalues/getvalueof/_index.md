---
title: GetValueOf()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de verpakte waarde van de enum-constante met de opgegeven naam.
type: docs
weight: 53
url: /nl/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const methode


Retourneert de verpakte waarde van de enum-constante met de opgegeven naam.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../string/)\& | De naam van de enum-constante |
| ignoreCase | **bool** | Specificeert of de hoofdlettergevoeligheid moet worden genegeerd bij het interpreteren van de naam van de enum-constante |

### Retourwaarde

Een verpakte waarde van de enum-constante waarvan de naam is gespecificeerd in **str**.

## EnumValues::GetValueOf(long) const methode


Retourneert de verpakte waarde van de enum-constante met de opgegeven waarde.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| val | long | De waarde van de enum-constante |

### Retourwaarde

Een verpakte waarde van de enum-constante waarvan de waarde is gespecificeerd in **str**.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [String](../../string/)
* Klasse [EnumValues](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)