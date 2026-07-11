---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Επιτρέπει τη δημιουργία παρουσίασης μέσω διεπαφής COM
type: docs
url: /el/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Επιτρέπει τη δημιουργία παρουσίασης μέσω διεπαφής COM.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createPresentation()](#createPresentation--) | Δημιουργεί νέα παρουσίαση. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Δημιουργεί νέα παρουσίαση με πρόσθετες επιλογές φόρτωσης |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Λαμβάνει πληροφορίες για την παρουσίαση στο καθορισμένο αρχείο. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Λαμβάνει πληροφορίες για την παρουσίαση σε καθορισμένη ροή. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα με πρόσθετες επιλογές φόρτωσης |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Διαβάζει υπάρχουσα παρουσίαση από ροή |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Διαβάζει υπάρχουσα παρουσίαση από αρχείο |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |

### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Δημιουργεί νέα παρουσίαση.

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Νέα παρουσίαση

### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
```

Δημιουργεί νέα παρουσίαση με πρόσθετες επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Νέα παρουσίαση

### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public abstract IPresentationInfo getPresentationInfo(String file)
```

Λαμβάνει πληροφορίες για την παρουσίαση στο καθορισμένο αρχείο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο παρουσίασης. |

**Επιστρέφει:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Πληροφορίες παρουσίασης

### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Λαμβάνει πληροφορίες για την παρουσίαση σε καθορισμένη ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή παρουσίασης. |

**Επιστρέφει:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Πληροφορίες παρουσίασης.

### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Διαβάζει υπάρχουσα παρουσίαση από πίνακα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας για ανάγνωση |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Διαβάζει υπάρχουσα παρουσίαση από πίνακα με πρόσθετες επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας για ανάγνωση |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Διαβάζει υπάρχουσα παρουσίαση από ροή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου για ανάγνωση |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου για ανάγνωση |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Διαβάζει υπάρχουσα παρουσίαση από αρχείο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Όνομα αρχείου |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Όνομα αρχείου |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση

### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο εισόδου |
| mode | int | Λειτουργία εξαγωγής |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Το στιγμιότυπο του PresentationText που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών

### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Το στιγμιότυπο του PresentationText που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών

### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Το στιγμιότυπο του PresentationText που περιέχει τον πίνακα SlideText που αντιπροσωπεύει το ακατέργαστο κείμενο των διαφανειών