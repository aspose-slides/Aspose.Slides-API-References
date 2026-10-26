---
title: GetNameValueListLength()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar en given sträng från det angivna indexet till samlingen av NameValueHeaderValue-klassinstanser och returnerar längden på en parsad delsträng.
type: docs
weight: 131
url: /sv/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) metod

Konverterar en given sträng från det angivna indexet till samlingen av NameValueHeaderValue-klassinstanser och returnerar längden på en parsad delsträng.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [String](../../../system/string/) | En sträng att analysera. |
| startIndex | **int32_t** | En startposition för analys. |
| delimiter | char16_t | En sträng som används för att avgränsa objekt i den angivna strängen. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Utdata-parameter där en parsad samling kommer att tilldelas. |

### Returvärde

Längden på en parsad delsträng.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [ObjectCollection](../../objectcollection/)
* Klass [NameValueHeaderValue](../)
* Namnrymd [System::Net::Http::Headers](../../)
* Bibliotek [Aspose.Slides](../../../)