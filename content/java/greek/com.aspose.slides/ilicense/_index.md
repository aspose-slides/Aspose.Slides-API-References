---
title: ILicense
second_title: Aspose.Slides for Java API Reference
description: Provides methods to license the component.
type: docs
url: /el/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Παρέχει μεθόδους για την άδεια του στοιχείου.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Methods

| Method | Description |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Παρέχει άδεια στο στοιχείο. |
| [resetLicense()](#resetLicense--) | Επαναφορά της άδειας |
| [isLicensed()](#isLicensed--) | Έλεγχος εάν η άδεια έχει εφαρμοστεί στο στοιχείο |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```

Παρέχει άδεια στο στοιχείο.

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
| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Σαφής διαδρομή.

2. Ο φάκελος του assembly του στοιχείου.

3. Ο φάκελος του assembly που καλεί ο πελάτης.

4. Ο φάκελος του entry assembly.

5. Ένας ενσωματωμένος πόρος στο assembly που καλεί ο πελάτης. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```

Παρέχει άδεια στο στοιχείο.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Μια ροή που περιέχει την άδεια. |

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ροή. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```

Επαναφορά της άδειας

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

Έλεγχος εάν η άδεια έχει εφαρμοστεί στο στοιχείο

**Επιστρέφει:**
boolean - true αν το στοιχείο είναι αδειοδοτημένο, διαφορετικά false