---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Analog till C# Object.ToString()-metoden. Gör det möjligt att konvertera anpassade objekt till sträng.
type: docs
weight: 79
url: /sv/system.net.http.headers/namevalueheadervalue/tostring/
---
## NameValueHeaderValue::ToString() const metod

Analog till C# [Object.ToString()](../../../system/object/tostring/) metod. Gör det möjligt att konvertera anpassade objekt till sträng.

```cpp
String System::Net::Http::Headers::NameValueHeaderValue::ToString() const override
```

### Returvärde

[String](../../../system/string/) representation som tillhandahålls av slutlig klass.

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool, System::SharedPtr\<Text::StringBuilder\>) metod

Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser.

```cpp
static void System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator, System::SharedPtr<Text::StringBuilder> destination)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Samlingen av NameValueHeaderValue-klassinstanser. |
| separator | char16_t | En strängseparator. |
| leadingSeparator | **bool** | Det värde som indikerar om strängseparatorn måste läggas till före det första samlingsobjektet. |
| destination | [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\> | En instans där en strängrepresentation kommer att tilldelas. |

## NameValueHeaderValue::ToString(System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>, char16_t, bool) metod

Returnerar en strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser.

```cpp
static String System::Net::Http::Headers::NameValueHeaderValue::ToString(System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> values, char16_t separator, bool leadingSeparator)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Samlingen av NameValueHeaderValue-klassinstanser. |
| separator | char16_t | En strängseparator. |
| leadingSeparator | **bool** | Det värde som indikerar om strängseparatorn måste läggas till före det första samlingsobjektet. |

### Returvärde

En strängrepresentation av samlingen av NameValueHeaderValue-klassinstanser.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [NameValueHeaderValue](../)
* Klass [ObjectCollection](../../objectcollection/)
* Klass [StringBuilder](../../../system.text/stringbuilder/)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)