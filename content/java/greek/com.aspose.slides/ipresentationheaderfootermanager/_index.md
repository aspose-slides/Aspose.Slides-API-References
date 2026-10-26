---
title: IPresentationHeaderFooterManager
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει το διαχειριστή που διατηρεί τη συμπεριφορά όλων των placeholders υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της παρουσίασης.
type: docs
url: /el/com.aspose.slides/ipresentationheaderfootermanager/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Αντιπροσωπεύει το διαχειριστή που διαχειρίζεται τη συμπεριφορά όλων των placeholders υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας της παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Αλλάζει την ορατότητα όλων των placeholders κεφαλίδας, συμπεριλαμβανομένου του notes master, των notes slides και του handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Αλλάζει την ορατότητα όλων των placeholders υποσέλιδου, συμπεριλαμβανομένων των master slides, των layout slides και των slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Αλλάζει την ορατότητα όλων των placeholders αριθμού σελίδας, συμπεριλαμβανομένων των master slides, των layout slides και των slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Αλλάζει την ορατότητα όλων των placeholders ημερομηνίας-ώρας, συμπεριλαμβανομένων των master slides, των layout slides και των slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Ορίζει κείμενο σε όλα τα placeholders κεφαλίδας, συμπεριλαμβανομένου του notes master, των notes slides και του handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Ορίζει κείμενο σε όλα τα placeholders υποσέλιδου, συμπεριλαμβανομένων των master slides, των layout slides και των slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Ορίζει κείμενο σε όλα τα placeholders ημερομηνίας-ώρας, συμπεριλαμβανομένων των master slides, των layout slides και των slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Αλλάζει την ορατότητα των placeholders υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλες τις διαφάνειες τίτλου και για την πρώτη διαφάνεια διάταξης. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα όλων των placeholders κεφαλίδας, συμπεριλαμβανομένου του notes master, των notes slides και του handout master.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholders κεφαλίδας ορατά, διαφορετικά - τα κρύβει. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα όλων των placeholders υποσέλιδου, συμπεριλαμβανομένων των master slides, των layout slides και των slides.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholders υποσέλιδου ορατά, διαφορετικά - τα κρύβει. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα όλων των placeholders αριθμού σελίδας, συμπεριλαμβανομένων των master slides, των layout slides και των slides.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholders αριθμού σελίδας ορατά, διαφορετικά - τα κρύβει. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Αλλάζει την ορατότητα όλων των placeholders ημερομηνίας-ώρας, συμπεριλαμβανομένων των master slides, των layout slides και των slides.

**Παραμέτροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholders ημερομηνίας-ώρας ορατά, διαφορετικά - τα κρύβει. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Ορίζει κείμενο σε όλα τα placeholders κεφαλίδας, συμπεριλαμβανομένου του notes master, των notes slides και του handout master.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Ορίζει κείμενο σε όλα τα placeholders υποσέλιδου, συμπεριλαμβανομένων των master slides, των layout slides και των slides.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Ορίζει κείμενο σε όλα τα placeholders ημερομηνίας-ώρας, συμπεριλαμβανομένων των master slides, των layout slides και των slides.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | Κείμενο προς ορισμό. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Αλλάζει την ορατότητα των placeholders υποσέλιδου, ημερομηνίας-ώρας και αριθμού σελίδας για όλες τις διαφάνειες τίτλου και για την πρώτη διαφάνεια διάταξης. Title slides \\u2013 διαφάνειες που βασίζονται στην πρώτη διαφάνεια διάταξης (ανεξάρτητα από τον τύπο αυτής της πρώτης διάταξης).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| isVisible | boolean | true - καθιστά τα placeholders ορατά, διαφορετικά - τα κρύβει. |