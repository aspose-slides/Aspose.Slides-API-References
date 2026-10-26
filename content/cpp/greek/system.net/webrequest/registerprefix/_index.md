---
title: RegisterPrefix()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καταχωρίζει το απόγονο WebRequest για το καθορισμένο URI.
type: docs
weight: 92
url: /el/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) μέθοδος

Καταχωρίζει το [WebRequest](../) απόγονο για το καθορισμένο URI.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Το URI ή το πρόθεμα του URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Δημιουργεί νέες περιπτώσεις της κλάσης [WebRequest](../). |

### Τιμή Επιστροφής

Αληθές όταν το [WebRequest](../) απόγονο καταχωρείται επιτυχώς για το καθορισμένο URI, διαφορετικά ψευδές.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IWebRequestCreate](../../iwebrequestcreate/)
* Κλάση [WebRequest](../)
* Χώρος ονομάτων [System::Net](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)