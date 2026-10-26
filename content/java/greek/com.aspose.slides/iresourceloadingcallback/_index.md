---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Java API Reference
description: Διεπαφή callback που χρησιμοποιείται για τη διαχείριση φόρτωσης εξωτερικών πόρων.
type: docs
url: /el/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Διεπαφή callback που χρησιμοποιείται για τη διαχείριση φόρτωσης εξωτερικών πόρων.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Μέθοδος callback που ρυθμίζει τη φόρτωση εξωτερικών πόρων. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Μέθοδος callback που ρυθμίζει τη φόρτωση εξωτερικών πόρων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Δεδομένα φόρτωσης πόρου [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Επιστρέφει:**
int - Η απόφαση φόρτωσης πόρου [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).