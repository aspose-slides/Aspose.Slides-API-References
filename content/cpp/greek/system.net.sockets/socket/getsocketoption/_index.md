---
title: GetSocketOption()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.
type: docs
weight: 729
url: /el/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) μέθοδος

Επιστρέφει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Το επίπεδο επιλογής της υποδοχής. |
| optionName | [SocketOptionName](../../socketoptionname/) | Το όνομα της επιλογής. |

### Τιμή Επιστροφής

Η τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) μέθοδος

Αποκτά την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Το επίπεδο επιλογής της υποδοχής. |
| optionName | [SocketOptionName](../../socketoptionname/) | Το όνομα της επιλογής. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Η παράμετρος εξόδου όπου θα εκχωρηθεί η αντίστοιχη τιμή. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) μέθοδος

Επιστρέφει την τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Το επίπεδο επιλογής της υποδοχής. |
| optionName | [SocketOptionName](../../socketoptionname/) | Το όνομα της επιλογής. |
| optionLength | **int32_t** | Το μήκος της επιλογής. |

### Τιμή Επιστροφής

Η τιμή που αντιστοιχεί στο καθορισμένο όνομα επιλογής.

## Δείτε επίσης

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Socket](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)