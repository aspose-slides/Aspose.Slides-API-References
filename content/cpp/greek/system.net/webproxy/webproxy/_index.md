---
title: WebProxy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια νέα παρουσία.
type: docs
weight: 131
url: /el/system.net/webproxy/webproxy/
---
## WebProxy::WebProxy() κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy()
```

## WebProxy::WebProxy(System::SharedPtr\<Uri\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Διεύθυνση του διακομιστή διαμεσολάβησης. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Η λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή διαμεσολάβησης. |

## WebProxy::WebProxy(System::SharedPtr\<Uri\>, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(System::SharedPtr<Uri> Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Η λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή διαμεσολάβησης. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Τα διαπιστευτήρια που αποστέλλονται στον διακομιστή διαμεσολάβησης για πιστοποίηση. |

## WebProxy::WebProxy(String, int32_t) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(String Host, int32_t Port)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Host | [String](../../../system/string/) | Το όνομα κεντρικού υπολογιστή. |
| Port | **int32_t** | Ο αριθμός θύρας. |

## WebProxy::WebProxy(String) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(String Address)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Διεύθυνση του διακομιστή διαμεσολάβησης. |

## WebProxy::WebProxy(String, bool) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Η λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή διαμεσολάβησης. |

## WebProxy::WebProxy(String, bool, System::ArrayPtr\<String\>, System::SharedPtr\<ICredentials\>) κατασκευαστής

Δημιουργεί μια νέα παρουσία.

```cpp
System::Net::WebProxy::WebProxy(String Address, bool BypassOnLocal, System::ArrayPtr<String> BypassList, System::SharedPtr<ICredentials> Credentials)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Address | [String](../../../system/string/) | Διεύθυνση του διακομιστή διαμεσολάβησης. |
| BypassOnLocal | **bool** | Τιμή που υποδεικνύει εάν ο διακομιστής διαμεσολάβησης πρέπει να χρησιμοποιηθεί για τοπικές διευθύνσεις. |
| BypassList | [System::ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\> | Η λίστα των διευθύνσεων που δεν χρησιμοποιούν τον διακομιστή διαμεσολάβησης. |
| Credentials | [System::SharedPtr](../../../system/sharedptr/)\<[ICredentials](../../icredentials/)\> | Τα διαπιστευτήρια που αποστέλλονται στον διακομιστή διαμεσολάβησης για πιστοποίηση. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [WebProxy](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [ICredentials](../../icredentials/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)