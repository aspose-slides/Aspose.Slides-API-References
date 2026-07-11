---
title: ITrendline
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς γραφήματος
type: docs
url: /el/com.aspose.slides/itrendline/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Η κλάση αντιπροσωπεύει τη γραμμή τάσης της σειράς διαγράμματος
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. |
| [getTrendlineType()](#getTrendlineType--) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. |
| [getFormat()](#getFormat--) | Αναπαριστά τη μορφή της γραμμής τάσης. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Αναπαριστά τη μορφή της γραμμής τάσης. |
| [getBackward()](#getBackward--) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα για τη σειρά που ακολουθείται. |
| [setBackward(double value)](#setBackward-double-) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα για τη σειρά που ακολουθείται. |
| [getForward()](#getForward--) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα για τη σειρά που ακολουθείται. |
| [setForward(double value)](#setForward-double-) | Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα για τη σειρά που ακολουθείται. |
| [getIntercept()](#getIntercept--) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. |
| [setIntercept(double value)](#setIntercept-double-) | Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. |
| [getDisplayEquation()](#getDisplayEquation--) | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). |
| [getOrder()](#getOrder--) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. |
| [setOrder(byte value)](#setOrder-byte-) | Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. |
| [getPeriod()](#getPeriod--) | Καθορίζει την περίοδο της γραμμής τάσης για γραμμή τάσης κινητού μέσου. |
| [setPeriod(byte value)](#setPeriod-byte-) | Καθορίζει την περίοδο της γραμμής τάσης για γραμμή τάσης κινητού μέσου. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την εξίσωση). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την εξίσωση). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Αναπαριστά την καταχώρηση υπομνήματος που σχετίζεται με αυτήν τη γραμμή τάσης Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Λαμβάνει ή ορίζει το όνομα της γραμμής τάσης. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/εγγραφή [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Επιστρέφει:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Λαμβάνει ή ορίζει τον τύπο της γραμμής τάσης. Ανάγνωση/εγγραφή [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Αναπαριστά τη μορφή της γραμμής τάσης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Επιστρέφει:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Αναπαριστά τη μορφή της γραμμής τάσης. Ανάγνωση/εγγραφή [IFormat](../../com.aspose.slides/iformat).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα για τη σειρά που ακολουθείται. Σε διαγράμματα διασποράς και μη διασποράς, η τιμή πρέπει να είναι μη αρνητική. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται πριν από τα δεδομένα για τη σειρά που ακολουθείται. Σε διαγράμματα διασποράς και μη διασποράς, η τιμή πρέπει να είναι μη αρνητική. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα για τη σειρά που ακολουθείται. Σε διαγράμματα διασποράς και μη διασποράς, η τιμή πρέπει να είναι μη αρνητική. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Καθορίζει τον αριθμό των κατηγοριών (ή μονάδων σε διάγραμμα διασποράς) που η γραμμή τάσης επεκτείνεται μετά τα δεδομένα για τη σειρά που ακολουθείται. Σε διαγράμματα διασποράς και μη διασποράς, η τιμή πρέπει να είναι μη αρνητική. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/εγγραφή double.

**Επιστρέφει:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Καθορίζει την τιμή όπου η γραμμή τάσης θα διασχίσει τον άξονα y. Αυτή η ιδιότητα υποστηρίζεται μόνο όταν ο τύπος γραμμής τάσης είναι exp, linear ή poly. Ανάγνωση/εγγραφή double.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Καθορίζει ότι η εξίσωση της γραμμής τάσης εμφανίζεται στο διάγραμμα (στο ίδιο ετικέτα με την τιμή Rsquaredvalue). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Καθορίζει τη σειρά της πολυωνυμικής γραμμής τάσης. Αγνοείται για άλλους τύπους. Η τιμή πρέπει να είναι μεταξύ 2 και 6. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Καθορίζει την περίοδο της γραμμής τάσης για γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/εγγραφή byte.

**Επιστρέφει:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Καθορίζει την περίοδο της γραμμής τάσης για γραμμή τάσης κινητού μέσου. Αγνοείται για άλλες παραλλαγές. Η τιμή πρέπει να είναι μεταξύ 2 και 255. Ανάγνωση/εγγραφή byte.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την εξίσωση). Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Καθορίζει ότι η τιμή R-squared της γραμμής τάσης εμφανίζεται στο διάγραμμα (στην ίδια ετικέτα με την εξίσωση). Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Αναπαριστά την καταχώρηση υπομνήματος που σχετίζεται με αυτήν τη γραμμή τάσης Μόνο για ανάγνωση [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Επιστρέφει:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)