---
title: HttpHeaderValueCollection()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक नया उदाहरण बनाता है।
type: docs
weight: 40
url: /hi/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) निर्माता

एक नया उदाहरण बनाता है।

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | हेडर का नाम। |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP हेडर्स का संग्रह। |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) निर्माता

एक नया उदाहरण बनाता है।

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | हेडर का नाम। |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP हेडर्स का संग्रह। |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | जो डेलीगेट जोड़े गए आइटम्स को मान्य करने के लिए उपयोग किया जाता है। |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) निर्माता

एक नया उदाहरण बनाता है।

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | हेडर का नाम। |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP हेडर्स का संग्रह। |
| specialValue | T | "विशेष मान"। |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) निर्माता

एक नया उदाहरण बनाता है।

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | हेडर का नाम। |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | HTTP हेडर्स का संग्रह। |
| specialValue | T | "विशेष मान"। |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | जो डेलीगेट जोड़े गए आइटम्स को मान्य करने के लिए उपयोग किया जाता है। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [String](../../../system/string/)
* Class [HttpHeaders](../../httpheaders/)
* Class [HttpHeaderValueCollection](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)