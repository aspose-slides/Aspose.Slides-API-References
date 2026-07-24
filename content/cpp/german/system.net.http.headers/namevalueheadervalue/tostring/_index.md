---
title: ToString()
second_title: Aspose.Slides für C++ API-Referenz
description: Analog zur C#-Methode Object.ToString(). Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String.
type: docs
weight: 79
url: /de/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const Methode

Analog zur C#-Methode [Object.ToString()](../../../system/object/tostring/). Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Rückgabewert

[String](../../../system/string/) Darstellung, wie von der endgültigen Klasse bereitgestellt.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) Methode

Gibt eine String-Darstellung der Sammlung von NameValueHeaderValue-Klasseninstanzen zurück.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Die Sammlung von NameValueHeaderValue-Klasseninstanzen. |
| separator | char16_t | Ein Zeichenfolgen-Trennzeichen. |
| leadingSeparator | **bool** | Der Wert, der angibt, ob das Zeichenfolgen-Trennzeichen vor dem ersten Sammlungs-Element hinzugefügt werden muss. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Eine Instanz, der eine String-Darstellung zugewiesen wird. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) Methode

Gibt eine String-Darstellung der Sammlung von NameValueHeaderValue-Klasseninstanzen zurück.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Die Sammlung von NameValueHeaderValue-Klasseninstanzen. |
| separator | char16_t | Ein Zeichenfolgen-Trennzeichen. |
| leadingSeparator | **bool** | Der Wert, der angibt, ob das Zeichenfolgen-Trennzeichen vor dem ersten Sammlungs-Element hinzugefügt werden muss. |

### Rückgabewert

Eine String-Darstellung der Sammlung von NameValueHeaderValue-Klasseninstanzen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [NameValueHeaderValue](../)
* Klasse [ObjectCollection](../../objectcollection/)
* Klasse [StringBuilder](../../../system.text/stringbuilder/)
* Namensraum [System::Net::Http::Headers](../../)
* Bibliothek [Aspose.Slides](../../../)