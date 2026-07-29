---
title: GetNameValueLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från det angivna indexet till en instans av klassen NameValueHeaderValue.
type: docs
weight: 118
url: /sv/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) metod


Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för analysering. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | En instans där ett analyserat objekt kommer att tilldelas. |

### Returvärde

Returnerar längden på en analyserad delsträng, annars 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) metod


Konverterar en given sträng från det angivna indexet till en instans av klassen [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för analysering. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | En funktion som används för att skapa nya instanser av klassen [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | En instans där ett analyserat objekt kommer att tilldelas. |

### Returvärde

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Klass [String](../../../system/string/)
* Klass [NameValueHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)