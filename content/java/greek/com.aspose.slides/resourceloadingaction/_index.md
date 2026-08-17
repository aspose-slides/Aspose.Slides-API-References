---
title: ResourceLoadingAction
second_title: Aspose.Slides για την Αναφορά API Java
description: Καθορίζει τη λειτουργία φόρτωσης εξωτερικών πόρων.
type: docs
url: /el/com.aspose.slides/resourceloadingaction/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Καθορίζει τη λειτουργία φόρτωσης εξωτερικών πόρων.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Default](#Default) | Το Aspose.Slides θα φορτώσει τον εξωτερικό πόρο όπως συνήθως. |
| [Skip](#Skip) | Το Aspose.Slides θα παραλείψει τη φόρτωση του εξωτερικού πόρου. |
| [UserProvided](#UserProvided) | Το Aspose.Slides θα χρησιμοποιήσει τον πίνακα byte που παρέχεται από τον χρήστη στο [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) ως δεδομένα εικόνας. |
### Προεπιλογή {#Default}
```
public static final int Default
```

Το Aspose.Slides θα φορτώσει τον εξωτερικό πόρο όπως συνήθως.

### Παράλειψη {#Skip}
```
public static final int Skip
```

Το Aspose.Slides θα παραλείψει τη φόρτωση του εξωτερικού πόρου. Μόνο ο σύνδεσμος χωρίς δεδομένα θα αποθηκευτεί για μια εικόνα.

### Παρεχόμενο από Χρήστη {#UserProvided}
```
public static final int UserProvided
```

Το Aspose.Slides θα χρησιμοποιήσει τον πίνακα byte που παρέχεται από τον χρήστη στο [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) ως δεδομένα εικόνας.