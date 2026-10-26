---
title: License
second_title: Αναφορά API του Aspose.Slides για Android μέσω Java
description: Παρέχει μεθόδους για την άδεια του στοιχείου.
type: docs
url: /el/com.aspose.slides/license/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Παρέχει μεθόδους για την άδεια του στοιχείου.

```
Σε αυτό το παράδειγμα, θα γίνει προσπάθεια εύρεσης ενός αρχείου άδειας με όνομα MyLicense.lic
 σε φάκελο που περιέχει το στοιχείο, σε φάκελο που περιέχει το καλούν assembly,
 σε φάκελο του entry assembly και στη συνέχεια στους ενσωματωμένους πόρους του καλούν assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσσας. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Δίνει άδεια στο στοιχείο. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Δίνει άδεια στο στοιχείο. |
| [getVersion()](#getVersion--) | Επιστρέφει τη έκδοση του Aspose.Slides for Android μέσω Java. |
| [resetLicense()](#resetLicense--) | Επαναφέρει την άδεια. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Αρχικοποιεί μια νέα παρουσία αυτής της κλάσσας.

```
Σε αυτό το παράδειγμα, θα γίνει προσπάθεια εύρεσης ενός αρχείου άδειας με όνομα MyLicense.lic
 σε φάκελο που περιέχει το στοιχείο, σε φάκελο που περιέχει το καλούν assembly,
 σε φάκελο του entry assembly και στη συνέχεια στους ενσωματωμένους πόρους του καλούν assembly.
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


Δίνει άδεια στο στοιχείο.

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
| stream | java.io.InputStream | Μια ροή που περιέχει την άδεια. Χρησιμοποιήστε null για να μεταβείτε σε λειτουργία αξιολόγησης. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Δίνει άδεια στο στοιχείο.

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
| namePath | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Επιστρέφει τη έκδοση του Aspose.Slides for Android μέσω Java.

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


Ελέγχει αν η άδεια έχει εφαρμοστεί στο στοιχείο

**Επιστρέφει:**
boolean