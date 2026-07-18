---
title: GetHostByAddress()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί μια νέα IPHostEntry-class παρουσία χρησιμοποιώντας την καθορισμένη αναπαράσταση συμβολοσειράς μιας διεύθυνσης IP.
type: docs
weight: 14
url: /el/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) μέθοδος


Δημιουργεί μια νέα IPHostEntry-class παρουσία χρησιμοποιώντας την καθορισμένη αναπαράσταση συμβολοσειράς μιας διεύθυνσης IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [String](../../../system/string/) | Η αναπαράσταση συμβολοσειράς μιας διεύθυνσης IP. |

### Return Value

Μια νέα δημιουργημένη IPHostEntry-class παρουσία.

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) μέθοδος


Δημιουργεί μια νέα IPHostEntry-class παρουσία χρησιμοποιώντας την καθορισμένη διεύθυνση IP.

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | Η διεύθυνση IP. |

### Return Value

Μια νέα δημιουργημένη IPHostEntry-class παρουσία.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPHostEntry](../../iphostentry/)
* Κλάση [String](../../../system/string/)
* Κλάση [Dns](../)
* Κλάση [IPAddress](../../ipaddress/)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)