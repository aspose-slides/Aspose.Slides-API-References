---
title: ToString()
second_title: Aspose.Slides pro C++ – reference API
description: Analog metody Object.ToString() v C#. Umožňuje převádět vlastní objekty na řetězec.
type: docs
weight: 79
url: /cs/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const metoda

Analog metody C# [Object.ToString()](../../../system/object/tostring/). Umožňuje převádět vlastní objekty na řetězec.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Návratová hodnota

[String](../../../system/string/) reprezentace, jak je poskytována finální třídou.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) metoda

Vrací řetězcovou reprezentaci kolekce instancí třídy NameValueHeaderValue.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Kolekce instancí třídy NameValueHeaderValue. |
| separator | char16_t | Řetězcový oddělovač. |
| leadingSeparator | **bool** | Hodnota, která určuje, zda má být řetězcový oddělovač přidán před první položku kolekce. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Instance, do které bude přiřazena řetězcová reprezentace. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) metoda

Vrací řetězcovou reprezentaci kolekce instancí třídy NameValueHeaderValue.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Kolekce instancí třídy NameValueHeaderValue. |
| separator | char16_t | Řetězcový oddělovač. |
| leadingSeparator | **bool** | Hodnota, která určuje, zda má být řetězcový oddělovač přidán před první položku kolekce. |

### Návratová hodnota

Řetězcová reprezentace kolekce instancí třídy NameValueHeaderValue.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [NameValueHeaderValue](../)
* Třída [ObjectCollection](../../objectcollection/)
* Třída [StringBuilder](../../../system.text/stringbuilder/)
* Jmenný prostor [System::Net::Http::Headers](../../)
* Knihovna [Aspose.Slides](../../../)