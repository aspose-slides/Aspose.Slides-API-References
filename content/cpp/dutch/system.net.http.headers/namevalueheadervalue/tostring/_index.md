---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Analoge van C# Object.ToString() methode. Staat conversie van aangepaste objecten naar een string toe.
type: docs
weight: 79
url: /nl/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const methode

Analog van C# [Object.ToString()](../../../system/object/tostring/) methode. Staat conversie van aangepaste objecten naar een string toe.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Retourwaarde

[String](../../../system/string/) representatie zoals geleverd door de finale klasse.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) methode

Retourneert een stringrepresentatie van de collectie van de NameValueHeaderValue-klasse-instanties.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | De collectie van de NameValueHeaderValue-klasse-instanties. |
| separator | char16_t | Een string-scheidingsteken. |
| leadingSeparator | **bool** | De waarde die aangeeft of het string-scheidingsteken moet worden toegevoegd vóór het eerste collectie-item. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Een instantie waarin een stringrepresentatie wordt toegewezen. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) methode

Retourneert een stringrepresentatie van de collectie van de NameValueHeaderValue-klasse-instanties.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | De collectie van de NameValueHeaderValue-klasse-instanties. |
| separator | char16_t | Een string-scheidingsteken. |
| leadingSeparator | **bool** | De waarde die aangeeft of het string-scheidingsteken moet worden toegevoegd vóór het eerste collectie-item. |

### Retourwaarde

Een stringrepresentatie van de collectie van de NameValueHeaderValue-klasse-instanties.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [NameValueHeaderValue](../)
* Klasse [ObjectCollection](../../objectcollection/)
* Klasse [StringBuilder](../../../system.text/stringbuilder/)
* Naamruimte [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)