---
title: VbaProject
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αναπαριστά έργο VBA με μακροεντολές παρουσίασης.
type: docs
url: /el/com.aspose.slides/vbaproject/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Αναπαριστά έργο VBA με μακροεντολές παρουσίασης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VbaProject()](#VbaProject--) | Αυτός ο κατασκευαστής δημιουργεί νέο έργο VBA από την αρχή. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Αυτός ο κατασκευαστής φορτώνει το έργο VBA από την δυαδική αναπαράσταση του κοντέινερ OLE. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει το όνομα του έργου VBA. |
| [getModules()](#getModules--) | Επιστρέφει τη λίστα όλων των μονάδων που περιέχονται στο έργο VBA. |
| [getReferences()](#getReferences--) | Επιστρέφει τη λίστα όλων των αναφορών που περιέχονται στο έργο VBA. |
| [toBinary()](#toBinary--) | Επιστρέφει τη δυαδική αναπαράσταση του έργου VBA ως κοντέινερ OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Δείχνει αν το VBAProject προστατεύεται με κωδικό πρόσβασης για την προβολή των ιδιοτήτων του έργου. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```

Αυτός ο κατασκευαστής δημιουργεί νέο έργο VBA από την αρχή. Το έργο θα δημιουργηθεί στην κωδικοσελίδα 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```

Αυτός ο κατασκευαστής φορτώνει το έργο VBA από την δυαδική αναπαράσταση του κοντέινερ OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```

Επιστρέφει το όνομα του έργου VBA. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```

Επιστρέφει τη λίστα όλων των μονάδων που περιέχονται στο έργο VBA. Μόνο ανάγνωση [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Επιστρέφει:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```

Επιστρέφει τη λίστα όλων των αναφορών που περιέχονται στο έργο VBA. Μόνο ανάγνωση [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Επιστρέφει:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```

Επιστρέφει τη δυαδική αναπαράσταση του έργου VBA ως κοντέινερ OLE

**Επιστρέφει:**
byte[] - Δυαδική αναπαράσταση του έργου VBA ως κοντέινερ OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Δείχνει αν το VBAProject προστατεύεται με κωδικό πρόσβασης για την προβολή των ιδιοτήτων του έργου. Μόνο ανάγνωση  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
boolean