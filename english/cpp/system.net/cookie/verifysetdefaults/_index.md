---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API Reference
description: Verifies and sets the default attribute's values.
type: docs
weight: 482
url: /cpp/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults([CookieVariant](../../cookievariant/), [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>, **bool**, [String](../../../system/string/), **bool**, **bool**) method


Verifies and sets the default attribute's values.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | The cookie's specification. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | The Uri-class instance that is used to initialize the internal fields. |
| isLocalDomain | **bool** | A value that indicates if the cookie is pushed into the the local domain. |
| localDomain | [String](../../../system/string/) | A local domain name. |
| setDefault | **bool** | A value that indicates if the cookie's attributes must be initialized using their default values. |
| shouldThrow | **bool** | A value that indicates if an exception should be thrown when the specified values are invalid. |

### Return Value

True when all values are valid, otherwise false.

## See Also

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)
