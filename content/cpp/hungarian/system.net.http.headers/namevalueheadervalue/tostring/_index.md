---
title: ToString()
second_title: Aspose.Slides C++ API hivatkozás
description: A C# Object.ToString() metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá alakítását.
type: docs
weight: 79
url: /hu/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const metódus

Analog of C# [Object.ToString()](../../../system/object/tostring/) metódus. Lehetővé teszi egyedi objektumok karakterlánccá alakítását.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```


### Visszatérési érték

[String](../../../system/string/) ábrázolás, ahogyan a végső osztály biztosítja.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) metódus


Visszaad egy karakterlánc ábrázolást a NameValueHeaderValue-class példányainak gyűjteményéről.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A NameValueHeaderValue-class példányainak gyűjteménye. |
| separator | char16_t | Karakterlánc elválasztó. |
| leadingSeparator | **bool** | Az érték, amely azt jelzi, hogy a karakterlánc elválasztót hozzá kell-e adni az első gyűjteményelem előtt. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | Egy példány, ahová a karakterlánc ábrázolás lesz hozzárendelve. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) metódus


Visszaad egy karakterlánc ábrázolást a NameValueHeaderValue-class példányainak gyűjteményéről.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | A NameValueHeaderValue-class példányainak gyűjteménye. |
| separator | char16_t | Karakterlánc elválasztó. |
| leadingSeparator | **bool** | Az érték, amely azt jelzi, hogy a karakterlánc elválasztót hozzá kell-e adni az első gyűjteményelem előtt. |

### Visszatérési érték

A NameValueHeaderValue-class példányainak gyűjteményének karakterlánc ábrázolása.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [NameValueHeaderValue](../)
* Osztály [ObjectCollection](../../objectcollection/)
* Osztály [StringBuilder](../../../system.text/stringbuilder/)
* Névterület [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)