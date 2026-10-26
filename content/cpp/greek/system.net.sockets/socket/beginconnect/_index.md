---
title: BeginConnect()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης.
type: docs
weight: 573
url: /el/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Παρακινεί μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Το απομακρυσμένο σημείο άκρου. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση κλήσης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη, χρησιμοποιούμενα για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκινήμένη ασύγχρονη λειτουργία σύνδεσης.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Παρακινεί μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Το όνομα του απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου κεντρικού υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση κλήσης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη, χρησιμοποιούμενα για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκινήμένη ασύγχρονη λειτουργία σύνδεσης.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Παρακινεί μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Η διεύθυνση IP του απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου κεντρικού υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση κλήσης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη, χρησιμοποιούμενα για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκινήμένη ασύγχρονη λειτουργία σύνδεσης.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος

Παρακινεί μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Οι διευθύνσεις IP του απομακρυσμένου κεντρικού υπολογιστή. |
| port | **int32_t** | Ο αριθμός θύρας του απομακρυσμένου κεντρικού υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μια συνάρτηση κλήσης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη, χρησιμοποιούμενα για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Τιμή Επιστροφής

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει τη ξεκινήμένη ασύγχρονη λειτουργία σύνδεσης.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [EndPoint](../../../system.net/endpoint/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Socket](../)
* Κλάση [String](../../../system/string/)
* Κλάση [IPAddress](../../../system.net/ipaddress/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)