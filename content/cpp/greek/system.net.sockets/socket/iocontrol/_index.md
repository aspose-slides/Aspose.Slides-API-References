---
title: IOControl()
second_title: Aspose.Slides για Αναφορά API C++
description: Ορίζει λειτουργίες χαμηλού επιπέδου για το socket.
type: docs
weight: 703
url: /el/system.net.sockets/socket/iocontrol/
---
## Socket::IOControl(int32_t, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) μέθοδος


Ορίζει λειτουργίες χαμηλού επιπέδου για το socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(int32_t ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ioControlCode | **int32_t** | Ο κώδικας ελέγχου της λειτουργίας που θα εκτελεστεί. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η συμβολοσειρά byte που περιέχει τα δεδομένα εισόδου. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η συμβολοσειρά byte που περιέχει τα δεδομένα εξόδου. |

### Τιμή Επιστροφής

Ο αριθμός των byte στην **optionOutValue** παράμετρο.

## Socket::IOControl(IOControlCode, System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) μέθοδος


Ορίζει λειτουργίες χαμηλού επιπέδου για το socket.

```cpp
int32_t System::Net::Sockets::Socket::IOControl(IOControlCode ioControlCode, System::ArrayPtr<uint8_t> optionInValue, System::ArrayPtr<uint8_t> optionOutValue)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ioControlCode | [IOControlCode](../../iocontrolcode/) | Ο κώδικας ελέγχου της λειτουργίας που θα εκτελεστεί. |
| optionInValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η συμβολοσειρά byte που περιέχει τα δεδομένα εισόδου. |
| optionOutValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η συμβολοσειρά byte που περιέχει τα δεδομένα εξόδου. |

### Τιμή Επιστροφής

Ο αριθμός των byte στην **optionOutValue** παράμετρο.

## Δείτε επίσης

* Enum [IOControlCode](../../iocontrolcode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Socket](../)
* ΧώροςΟνομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)