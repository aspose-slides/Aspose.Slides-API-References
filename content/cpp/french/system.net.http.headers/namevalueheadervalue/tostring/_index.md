---
title: ToString()
second_title: Référence API Aspose.Slides pour C++
description: Analogue de la méthode C# Object.ToString(). Permet de convertir des objets personnalisés en chaîne.
type: docs
weight: 79
url: /fr/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const méthode

Analogue de la méthode C# [Object.ToString()](../../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Valeur de retour

[String](../../../system/string/) représentation telle que fournie par la classe finale.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) méthode

Renvoie une représentation sous forme de chaîne de la collection d’instances de la classe NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La collection d’instances de la classe NameValueHeaderValue. |
| separator | char16_t | Un séparateur de chaîne. |
| leadingSeparator | **bool** | La valeur qui indique si le séparateur de chaîne doit être ajouté avant le premier élément de la collection. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Une instance où une représentation sous forme de chaîne sera assignée. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) méthode

Renvoie une représentation sous forme de chaîne de la collection d’instances de la classe NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | La collection d’instances de la classe NameValueHeaderValue. |
| separator | char16_t | Un séparateur de chaîne. |
| leadingSeparator | **bool** | La valeur qui indique si le séparateur de chaîne doit être ajouté avant le premier élément de la collection. |

### Valeur de retour

Une représentation sous forme de chaîne de la collection d’instances de la classe NameValueHeaderValue.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [NameValueHeaderValue](../)
* Classe [ObjectCollection](../../objectcollection/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)