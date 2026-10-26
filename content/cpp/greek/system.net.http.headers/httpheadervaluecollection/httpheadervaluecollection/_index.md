---
title: HttpHeaderValueCollection()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα νέο αντικείμενο.
type: docs
weight: 40
url: /el/system.net.http.headers/httpheadervaluecollection/httpheadervaluecollection/
---
## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Το όνομα της κεφαλίδας. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Η συλλογή των κεφαλίδων HTTP. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Το όνομα της κεφαλίδας. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Η συλλογή των κεφαλίδων HTTP. |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Ο αντιπρόσωπος που χρησιμοποιείται για την επικύρωση των προστεθειμένων αντικειμένων. |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Το όνομα της κεφαλίδας. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Η συλλογή των κεφαλίδων HTTP. |
| specialValue | T | Μια \"ειδική τιμή\". |

## HttpHeaderValueCollection::HttpHeaderValueCollection(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Http::Headers::HttpHeaderValueCollection<T>::HttpHeaderValueCollection(String headerName, System::SharedPtr<HttpHeaders> store, T specialValue, Action<System::SharedPtr<HttpHeaderValueCollection<T>>, T> validator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| headerName | [String](../../../system/string/) | Το όνομα της κεφαλίδας. |
| store | [System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaders](../../httpheaders/)\> | Η συλλογή των κεφαλίδων HTTP. |
| specialValue | T | Μια \"ειδική τιμή\". |
| validator | [Action](../../../system/action/)\<[System::SharedPtr](../../../system/sharedptr/)\<[HttpHeaderValueCollection](../)\<T\>\>, T\> | Ο αντιπρόσωπος που χρησιμοποιείται για την επικύρωση των προστεθειμένων αντικειμένων. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Κλάση [String](../../../system/string/)
* Κλάση [HttpHeaders](../../httpheaders/)
* Κλάση [HttpHeaderValueCollection](../)
* Χώρος ονομάτων [System::Net::Http::Headers](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)