---
title: ResolveUri()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιλύει το απόλυτο URI από το βασικό και τα σχετικά URI καλώντας το ResolveUri στο υποκείμενο XmlResolver.
type: docs
weight: 40
url: /el/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) method

Επιλύει το απόλυτο URI από το base και το relative URI καλώντας το **ResolveUri** στο υποκείμενο [XmlResolver](../../xmlresolver/).

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το βασικό URI που χρησιμοποιείται για την επίλυση του σχετικού URI. |
| relativeUri | [String](../../../system/string/) | Το URI προς επίλυση. Το URI μπορεί να είναι απόλυτο ή σχετικό. Εάν είναι απόλυτο, αυτή η τιμή αντικαθιστά πρακτικά την τιμή του **baseUri**. Εάν είναι σχετικό, συνδυάζεται με το **baseUri** ώστε να δημιουργηθεί ένα απόλυτο URI. |

### Return Value

Το απόλυτο URI ή **nullptr** εάν το σχετικό URI δεν μπορεί να επιλυθεί (επιστρέφεται καλώντας το **ResolveUri** στο υποκείμενο [XmlResolver](../../xmlresolver/)).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlSecureResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)