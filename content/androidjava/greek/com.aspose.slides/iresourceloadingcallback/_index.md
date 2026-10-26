---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android μέσω Java αναφοράς API
description: Διεπαφή callback που χρησιμοποιείται για τη διαχείριση της φόρτωσης εξωτερικών πόρων.
type: docs
url: /el/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Διεπαφή callback που χρησιμοποιείται για τη διαχείριση της φόρτωσης εξωτερικών πόρων.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Callback method which regulates external resources loading. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Μέθοδος callback που ρυθμίζει τη φόρτωση εξωτερικών πόρων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Τα δεδομένα φόρτωσης πόρου [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Επιστρέφει:**
int - Η απόφαση φόρτωσης πόρου [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).