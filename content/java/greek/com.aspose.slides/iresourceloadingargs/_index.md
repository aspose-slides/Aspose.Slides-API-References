---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Διεπαφή για εξωτερικά επιχειρήματα φόρτωσης πόρων.
type: docs
url: /el/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Διεπαφή για εξωτερικά επιχειρήματα φόρτωσης πόρων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Αρχικό URI του πόρου όπως καθορίζεται στην εισαχθείσα παρουσίαση. |
| [getUri()](#getUri--) | URI του πόρου που χρησιμοποιείται για λήψη εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI του πόρου που χρησιμοποιείται για λήψη εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Ορίζει τα δεδομένα που παρέχονται από το χρήστη για τον πόρο που χρησιμοποιείται εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

Αρχικό URI του πόρου όπως καθορίζεται στην εισαχθείσα παρουσίαση.

**Επιστρέφει:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

URI του πόρου που χρησιμοποιείται για λήψη εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Αρχικά ορίζεται στο αρχικό URI του πόρου, αλλά μπορεί να επανακαθοριστεί σε οποιαδήποτε τιμή.

**Επιστρέφει:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

URI του πόρου που χρησιμοποιείται για λήψη εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Αρχικά ορίζεται στο αρχικό URI του πόρου, αλλά μπορεί να επανακαθοριστεί σε οποιαδήποτε τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

Ορίζει τα δεδομένα που παρέχονται από το χρήστη για τον πόρο που χρησιμοποιείται εάν [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) επιστρέφει [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Παρεχόμενα δεδομένα του πόρου byte[] |