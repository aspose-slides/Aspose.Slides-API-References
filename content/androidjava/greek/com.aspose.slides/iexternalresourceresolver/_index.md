---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: Διεπαφή callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.
type: docs
url: /el/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Διεπαφή callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Επίλυση του απόλυτου URI από τα βασικά και σχετικά URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Αντιστοίχιση ενός URI σε αντικείμενο που περιέχει τον πραγματικό πόρο. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Επίλυση του απόλυτου URI από τα βασικά και σχετικά URI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | java.lang.String | Βασικό URI των αντικειμένων σύνδεσης |
| relativeUri | java.lang.String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

**Επιστρέφει:**
java.lang.String - Απόλυτο URI ή null εάν το σχετικό URI δεν μπορεί να επιλυθεί.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

Αντιστοίχιση ενός URI σε αντικείμενο που περιέχει τον πραγματικό πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | java.lang.String | Απόλυτο URI προς το αντικείμενο. |

**Επιστρέφει:**
java.io.InputStream - Ένα αντικείμενο InputStream ή null εάν ο πόρος δεν μπορεί να μεταδοθεί.