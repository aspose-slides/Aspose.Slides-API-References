---
title: License
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.
type: docs
url: /el/com.aspose.slides/license/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

**Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.**

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) | Αρχικοποιεί ένα νέο στιγμιότυπο αυτής της κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Αδειοδοτεί το στοιχείο. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Αδειοδοτεί το στοιχείο. |
| [getVersion()](#getVersion--) | Επιστρέφει την έκδοση του Aspose.Slides για Java. |
| [resetLicense()](#resetLicense--) | Επαναφέρει την άδεια. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Αρχικοποιεί ένα νέο στιγμιότυπο αυτής της κλάσης.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Αδειοδοτεί το στοιχείο.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα ρεύμα που περιέχει την άδεια. Χρησιμοποιήστε null για να μεταβείτε σε λειτουργία αξιολόγησης. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Αδειοδοτεί το στοιχείο.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| namePath | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε κενό συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Επιστρέφει την έκδοση του Aspose.Slides για Java.

**Επιστρέφει:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Επαναφέρει την άδεια. Χρησιμοποιήστε αυτή τη μέθοδο για να επαναφέρετε την άδεια στο στοιχείο.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Ελέγξτε αν η άδεια έχει εφαρμοστεί στο στοιχείο

**Επιστρέφει:**
boolean