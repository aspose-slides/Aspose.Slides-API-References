---
title: IVbaProject
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά το VBA project με μακροεντολές παρουσίασης.
type: docs
url: /el/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Αναπαριστά το VBA project με μακροεντολές παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getName()](#getName--) | Επιστρέφει το όνομα του VBA project. |
| [getModules()](#getModules--) | Επιστρέφει τη λίστα όλων των modules που περιλαμβάνονται στο VBA project. |
| [getReferences()](#getReferences--) | Επιστρέφει τη λίστα όλων των references που περιλαμβάνονται στο VBA project. |
| [toBinary()](#toBinary--) | Επιστρέφει την δυαδική αναπαράσταση του VBA project ως OLE container. |
| [isPasswordProtected()](#isPasswordProtected--) | Δείχνει αν το VBAProject είναι προστατευμένο με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. |
### getName() {#getName--}
```
public abstract String getName()
```

Επιστρέφει το όνομα του VBA project. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Επιστρέφει τη λίστα όλων των modules που περιλαμβάνονται στο VBA project. Μόνο για ανάγνωση [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Επιστρέφει:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Επιστρέφει τη λίστα όλων των references που περιλαμβάνονται στο VBA project. Μόνο για ανάγνωση [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Επιστρέφει:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Επιστρέφει την δυαδική αναπαράσταση του VBA project ως OLE container. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Δείχνει αν το VBAProject είναι προστατευμένο με κωδικό πρόσβασης για προβολή ιδιοτήτων του έργου. Μόνο για ανάγνωση boolean.

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