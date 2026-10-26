---
title: VbaProject
second_title: Aspose.Slides για την αναφορά API Java
description: Αντιπροσωπεύει VBA project με μακροεντολές παρουσίασης.
type: docs
url: /el/com.aspose.slides/vbaproject/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Αντιπροσωπεύει το VBA project με μακροεντολές παρουσίασης.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VbaProject()](#VbaProject--) | Αυτός ο κατασκευαστής δημιουργεί νέο VBA project από την αρχή. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Αυτός ο κατασκευαστής φορτώνει το VBA project από τη δυαδική αναπαράσταση του δοχείου OLE. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει το όνομα του VBA project. |
| [getModules()](#getModules--) | Επιστρέφει τη λίστα όλων των μονάδων που περιέχονται στο VBA project. |
| [getReferences()](#getReferences--) | Επιστρέφει τη λίστα όλων των αναφορών που περιέχονται στο VBA project. |
| [toBinary()](#toBinary--) | Επιστρέφει τη δυαδική αναπαράσταση του VBA project ως δοχείο OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Δείχνει εάν το VBAProject είναι προστατευμένο με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Αυτός ο κατασκευαστής δημιουργεί νέο VBA project από την αρχή. Το έργο θα δημιουργηθεί με κωδικοποίηση 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Αυτός ο κατασκευαστής φορτώνει το VBA project από τη δυαδική αναπαράσταση του δοχείου OLE.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Επιστρέφει το όνομα του VBA project. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Επιστρέφει τη λίστα όλων των μονάδων που περιέχονται στο VBA project. Μόνο για ανάγνωση [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Επιστρέφει:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Επιστρέφει τη λίστα όλων των αναφορών που περιέχονται στο VBA project. Μόνο για ανάγνωση [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Επιστρέφει:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Επιστρέφει τη δυαδική αναπαράσταση του VBA project ως δοχείο OLE

**Επιστρέφει:**
byte[] - Δυαδική αναπαράσταση του VBA project ως δοχείο OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Δείχνει εάν το VBAProject είναι προστατευμένο με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. Μόνο για ανάγνωση  boolean .

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