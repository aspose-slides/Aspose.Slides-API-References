---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.
type: docs
url: /el/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Παρέχει μεθόδους για την αδειοδότηση του στοιχείου.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Αδειοδοτεί το στοιχείο. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Αδειοδοτεί το στοιχείο. |
| [resetLicense()](#resetLicense--) | Επαναφέρει την άδεια |
| [isLicensed()](#isLicensed--) | Ελέγχει αν η άδεια έχει εφαρμοστεί στο στοιχείο |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Αδειοδοτεί το στοιχείο.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης.

--------------------

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.
2. Ο φάκελος του assembly του στοιχείου.
3. Ο φάκελος του assembly που καλείται από τον πελάτη.
4. Ο φάκελος του entry assembly.
5. Ένας ενσωματωμένος πόρος στο assembly που καλείται από τον πελάτη. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Αδειοδοτεί το στοιχείο.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα ρεύμα που περιέχει την άδεια.

--------------------

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ένα ρεύμα. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Επαναφέρει την άδεια

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Χρησιμοποιήστε αυτή τη μέθοδο για να επαναφέρετε την άδεια στο στοιχείο

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Ελέγχει αν η άδεια έχει εφαρμοστεί στο στοιχείο

**Επιστρέφει:**
boolean - true εάν το στοιχείο είναι αδειοδοτημένο, αλλιώς false