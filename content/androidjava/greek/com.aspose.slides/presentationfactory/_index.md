---
title: PresentationFactory
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Επιτρέπει τη δημιουργία παρουσίασης μέσω διεπαφής COM
type: docs
url: /el/com.aspose.slides/presentationfactory/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Επιτρέπει τη δημιουργία παρουσίασης μέσω COM διεπαφής

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getInstance()](#getInstance--) | Στατική παρουσία του εργοστασίου παρουσίασης. |
| [createPresentation()](#createPresentation--) | Δημιουργεί νέα παρουσίαση. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Δημιουργεί νέα παρουσίαση με επιπλέον επιλογές φόρτωσης |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Δημιουργεί νέο αντικείμενο PresentationInfo από αρχείο και συνδέει την παρουσίαση με αυτό. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο PresentationInfo από ροή και συνδέει την παρουσίαση με αυτό. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα με επιπλέον επιλογές φόρτωσης |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Διαβάζει υπάρχουσα παρουσίαση από ροή |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από ροή με επιπλέον επιλογές φόρτωσης |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Διαβάζει υπάρχουσα παρουσίαση από αρχείο |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Διαβάζει υπάρχουσα παρουσίαση από ροή με επιπλέον επιλογές φόρτωσης |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```


### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```


Στατική παρουσία του εργοστασίου παρουσίασης. Μόνο-ανάγνωση [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Επιστρέφει:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```


Δημιουργεί νέα παρουσίαση.

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Νέα παρουσίαση
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```


Δημιουργεί νέα παρουσίαση με επιπλέον επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Νέα παρουσίαση
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```


Δημιουργεί νέο αντικείμενο PresentationInfo από αρχείο και συνδέει την παρουσίαση με αυτό.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο παρουσίασης. |

**Επιστρέφει:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Πληροφορίες παρουσίασης συνδεδεμένες στην παρουσίαση.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```


Δημιουργεί νέο αντικείμενο PresentationInfo από ροή και συνδέει την παρουσίαση με αυτό. Λαμβάνει πληροφορίες για την παρουσίαση στη συγκεκριμένη ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή παρουσίασης. |

**Επιστρέφει:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Πληροφορίες παρουσίασης συνδεδεμένες στην παρουσίαση.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```


Διαβάζει υπάρχουσα παρουσίαση από πίνακα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας προς ανάγνωση |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```


Διαβάζει υπάρχουσα παρουσίαση από πίνακα με επιπλέον επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας προς ανάγνωση |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```


Διαβάζει υπάρχουσα παρουσίαση από ροή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου προς ανάγνωση |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```


Διαβάζει υπάρχουσα παρουσίαση από ροή με επιπλέον επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου προς ανάγνωση |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
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
public final IPresentation readPresentation(String file, ILoadOptions options)
```


Διαβάζει υπάρχουσα παρουσίαση από ροή με επιπλέον επιλογές φόρτωσης

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Όνομα αρχείου |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentation](../../com.aspose.slides/ipresentation) - Διαβασμένη παρουσίαση
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο εισόδου |
| mode | int | Λειτουργία εξαγωγής |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Η παρουσία του PresentationText που περιέχει τον πίνακα SlideText με το ακατέργαστο κείμενο των διαφανειών
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Η παρουσία του PresentationText που περιέχει τον πίνακα SlideText με το ακατέργαστο κείμενο των διαφανειών
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```


Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Επιλογές φόρτωσης |

**Επιστρέφει:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Η παρουσία του PresentationText που περιέχει τον πίνακα SlideText με το ακατέργαστο κείμενο των διαφανειών