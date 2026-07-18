---
title: BeginConnect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης.
type: docs
weight: 261
url: /el/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| host | [String](../../../system/string/) | Ένα όνομα απομακρυσμένου υπολογιστή. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μία συνάρτηση επανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Return Value

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκίνηθείσα ασύγχρονη λειτουργία σύνδεσης.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Η διεύθυνση IP ενός απομακρυσμένου υπολογιστή. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μία συνάρτηση επανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Return Value

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκίνηθείσα ασύγχρονη λειτουργία σύνδεσης.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) μέθοδος


Ξεκινά μια ασύγχρονη λειτουργία σύνδεσης.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Οι διευθύνσεις IP ενός απομακρυσμένου υπολογιστή. |
| port | **int32_t** | Μια θύρα του απομακρυσμένου υπολογιστή. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Μία συνάρτηση επανάκλησης που θα κληθεί όταν ολοκληρωθεί η λειτουργία. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Δεδομένα που παρέχονται από το χρήστη και χρησιμοποιούνται για τη μοναδική ταυτοποίηση κάθε ασύγχρονης λειτουργίας σύνδεσης. |

### Return Value

Ένα αντικείμενο [IAsyncResult](../../../system/iasyncresult/) που αντιπροσωπεύει την εκκίνηθείσα ασύγχρονη λειτουργία σύνδεσης.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IAsyncResult](../../../system/iasyncresult/)
* Κλάση [String](../../../system/string/)
* Κλάση [Object](../../../system/object/)
* Κλάση [TcpClient](../)
* Κλάση [IPAddress](../../../system.net/ipaddress/)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)