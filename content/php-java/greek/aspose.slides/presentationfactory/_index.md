---
title: PresentationFactory
second_title: Aspose.Sildes για PHP μέσω Αναφοράς API Java
description: 
type: docs

url: /el/aspose.slides/presentationfactory/
---
## PresentationFactory κλάση

 Επιτρέπει τη δημιουργία παρουσίασης μέσω διεπαφής COM

### PresentationFactory {#PresentationFactory}

| Όνομα | Περιγραφή |
| --- | --- |
| PresentationFactory() |  |

 **Επιστρέφει:**
PresentationFactory


---


### createPresentation {#createPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| createPresentation () | Δημιουργεί νέα παρουσίαση. |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### createPresentation {#createPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| createPresentation ([LoadOptions](../loadoptions)) | Δημιουργεί νέα παρουσίαση με πρόσθετες επιλογές φόρτωσης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [LoadOptions](../loadoptions) | Επιλογές φόρτωσης |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### getInstance {#getInstance}

| Όνομα | Περιγραφή |
| --- | --- |
| getInstance () | Στατική παρουσία του εργοστασίου παρουσίασης. Μόνο για ανάγνωση PresentationFactory. |

 **Επιστρέφει:**
PresentationFactory


---


### getPresentationInfo {#getPresentationInfo}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentationInfo (String) | Δημιουργεί νέο αντικείμενο PresentationInfo από αρχείο και συνδέει την παρουσίαση με αυτό. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Αρχείο παρουσίασης. |

 **Επιστρέφει:**
[PresentationInfo](../presentationinfo)


---


### getPresentationInfo {#getPresentationInfo}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentationInfo (InputStream) | Δημιουργεί νέο αντικείμενο PresentationInfo από ροή και συνδέει την παρουσίαση με αυτό. Λαμβάνει πληροφορίες για την παρουσίαση στην καθορισμένη ροή. |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή παρουσίασης. |

 **Επιστρέφει:**
[PresentationInfo](../presentationinfo)


---


### getPresentationText {#getPresentationText}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentationText (String, int) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Αρχείο εισόδου |
| mode | int | Λειτουργία εξαγωγής |

 **Επιστρέφει:**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentationText (InputStream, int) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |

 **Επιστρέφει:**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| Όνομα | Περιγραφή |
| --- | --- |
| getPresentationText (InputStream, int, [LoadOptions](../loadoptions)) | Ανακτά το ακατέργαστο κείμενο από τις διαφάνειες |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου |
| mode | int | Λειτουργία εξαγωγής |
| options | [LoadOptions](../loadoptions) | Επιλογές φόρτωσης |

 **Επιστρέφει:**
[PresentationText](../presentationtext)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (byte[]) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας για ανάγνωση |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (byte[], [LoadOptions](../loadoptions)) | Διαβάζει υπάρχουσα παρουσίαση από πίνακα με πρόσθετες επιλογές φόρτωσης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Πίνακας για ανάγνωση |
| options | [LoadOptions](../loadoptions) | Επιλογές φόρτωσης |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (InputStream) | Διαβάζει υπάρχουσα παρουσίαση από ροή |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου για ανάγνωση |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (InputStream, [LoadOptions](../loadoptions)) | Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | InputStream | Ροή εισόδου για ανάγνωση |
| options | [LoadOptions](../loadoptions) | Επιλογές φόρτωσης |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (String) | Διαβάζει υπάρχουσα παρουσίαση από αρχείο |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Όνομα αρχείου |

 **Επιστρέφει:**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| Όνομα | Περιγραφή |
| --- | --- |
| readPresentation (String, [LoadOptions](../loadoptions)) | Διαβάζει υπάρχουσα παρουσίαση από ροή με πρόσθετες επιλογές φόρτωσης |

 **Παράμετροι:**

| Όνομα | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | String | Όνομα αρχείου |
| options | [LoadOptions](../loadoptions) | Επιλογές φόρτωσης |

 **Επιστρέφει:**
[Presentation](../presentation)

---