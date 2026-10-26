---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα cookie στη συλλογή.
type: docs
weight: 105
url: /el/system.net/cookiecontainer/add/
---
## CookieContainer::Add(System::SharedPtr\<Cookie\>) μέθοδος

Προσθέτει ένα cookie στη συλλογή.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Το cookie προς προσθήκη. |

## CookieContainer::Add(System::SharedPtr\<Cookie\>, bool) μέθοδος

Προσθέτει ένα cookie στη συλλογή.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Cookie> cookie, bool throwOnError)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Το cookie προς προσθήκη. |
| throwOnError | **bool** | Μια τιμή που υποδεικνύει εάν θα γίνει εξαίρεση όταν προκύψει σφάλμα. |

## CookieContainer::Add(System::SharedPtr\<CookieCollection\>) μέθοδος

Αντιγράφει cookies από την καθορισμένη συλλογή στην τρέχουσα.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<CookieCollection> cookies)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Η συλλογή από την οποία θα αντιγραφούν τα cookies. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<Cookie\>) μέθοδος

Προσθέτει ένα cookie για το καθορισμένο URI.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<Cookie> cookie)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Ένα URI του cookie. |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Το cookie προς προσθήκη. |

## CookieContainer::Add(System::SharedPtr\<Uri\>, System::SharedPtr\<CookieCollection\>) μέθοδος

Αντιγράφει cookies από την καθορισμένη συλλογή για το καθορισμένο URI στην τρέχουσα συλλογή.

```cpp
void System::Net::CookieContainer::Add(System::SharedPtr<Uri> uri, System::SharedPtr<CookieCollection> cookies)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Ένα URI του cookie. |
| cookies | [System::SharedPtr](../../../system/sharedptr/)\<[CookieCollection](../../cookiecollection/)\> | Μια συλλογή cookies από την οποία πρέπει να αντιγραφούν. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Cookie](../../cookie/)
* Κλάση [CookieContainer](../)
* Κλάση [CookieCollection](../../cookiecollection/)
* Κλάση [Uri](../../../system/uri/)
* Χώρος ονομάτων [System::Net](../../)
* Library [Aspose.Slides](../../../)