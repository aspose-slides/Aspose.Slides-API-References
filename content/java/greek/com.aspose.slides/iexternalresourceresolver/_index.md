---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Διεπαφή κλήσης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.
type: docs
url: /el/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Διεπαφή κλήσης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Επιδιόρθει το απόλυτο URI από το βασικό και το σχετικό URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

Επιλύει το απόλυτο URI από το βασικό και το σχετικό URI.

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

Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | java.lang.String | Απόλυτο URI προς το αντικείμενο. |

**Επιστρέφει:**
java.io.InputStream - Ένα αντικείμενο InputStream ή null εάν ο πόρος δεν μπορεί να μεταδοθεί.