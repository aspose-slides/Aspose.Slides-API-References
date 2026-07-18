---
title: CreateHttp()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια νέα παρουσία της κλάσης WebRequest χρησιμοποιώντας το καθορισμένο URI.
type: docs
weight: 79
url: /el/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) μέθοδος

Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../) χρησιμοποιώντας το καθορισμένο URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| requestUriString | [String](../../../system/string/) | Το URI που χρησιμοποιείται για τη δημιουργία μιας νέας παρουσίας της κλάσης [WebRequest](../). |

### Τιμή επιστροφής

Μια νέα δημιουργημένη παρουσία της κλάσης WebRequest.

## Παρατηρήσεις

Θα εξαπολυθεί η εξαίρεση NotSupportedException όταν το καθορισμένο URI ξεκινά με οποιοδήποτε σχήμα εκτός από [http://](http://) ή [https://](https://).

## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) μέθοδος

Δημιουργεί μια νέα παρουσία της κλάσης [WebRequest](../) χρησιμοποιώντας το καθορισμένο URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| requestUri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI που χρησιμοποιείται για τη δημιουργία μιας νέας παρουσίας της κλάσης [WebRequest](../). |

### Τιμή επιστροφής

Μια νέα δημιουργημένη παρουσία της κλάσης WebRequest.

## Παρατηρήσεις

Θα εξαπολυθεί η εξαίρεση NotSupportedException όταν το καθορισμένο URI ξεκινά με οποιοδήποτε σχήμα εκτός από [http://](http://) ή [https://](https://).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Class [Uri](../../../system/uri/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)