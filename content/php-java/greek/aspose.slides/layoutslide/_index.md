---
title: LayoutSlide
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs
url: /el/aspose.slides/layoutslide/
---
## LayoutSlide κλάση

Αντιπροσωπεύει μια διάταξη διαφάνειας.

### getDependingSlides {#getDependingSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| getDependingSlides () | Επιστρέφει έναν πίνακα με όλες τις διαφάνειες που εξαρτώνται από αυτή τη διάταξη διαφάνειας. |

**Επιστρέφει:**
[Slide](../slide)

---

### getDrawingGuides {#getDrawingGuides}

| Όνομα | Περιγραφή |
| --- | --- |
| getDrawingGuides () | Επιστρέφει μια συλλογή από οδηγούς σχεδίασης για τη διάταξη διαφάνειας. Μόνο ανάγνωση IDrawingGuidesCollection |

**Επιστρέφει:**
[DrawingGuidesCollection](../drawingguidescollection)

---

### getHeaderFooterManager {#getHeaderFooterManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getHeaderFooterManager () | Επιστρέφει τη διαχείριση HeaderFooter της διάταξης διαφάνειας. Μόνο ανάγνωση ILayoutSlideHeaderFooterManager. |

**Επιστρέφει:**
[LayoutSlideHeaderFooterManager](../layoutslideheaderfootermanager)

---

### getLayoutType {#getLayoutType}

| Όνομα | Περιγραφή |
| --- | --- |
| getLayoutType () | Επιστρέφει τον τύπο διάταξης αυτής της διάταξης διαφάνειας. Μόνο ανάγνωση SlideLayoutType. |

**Επιστρέφει:**
byte

---

### getMasterSlide {#getMasterSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| getMasterSlide () | Επιστρέφει ή ορίζει τη κύρια διαφάνεια για μια διάταξη. Ανάγνωση/εγγραφή IMasterSlide. |

**Επιστρέφει:**
[MasterSlide](../masterslide)

---

### getPlaceholderManager {#getPlaceholderManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getPlaceholderManager () | Επιστρέφει τη διαχείριση placeholder της διάταξης διαφάνειας. Μόνο ανάγνωση ILayoutPlaceholderManager. |

**Επιστρέφει:**
[LayoutPlaceholderManager](../layoutplaceholdermanager)

---

### getShowMasterShapes {#getShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| getShowMasterShapes () | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
boolean

---

### getThemeManager {#getThemeManager}

| Όνομα | Περιγραφή |
| --- | --- |
| getThemeManager () | Επιστρέφει τη διαχείριση αντικατάστασης θέματος. Μόνο ανάγνωση IOverrideThemeManager. |

**Επιστρέφει:**
[SlideThemeManager](../slidethememanager), [LayoutSlideThemeManager](../layoutslidethememanager), [ChartThemeManager](../chartthememanager), [BaseOverrideThemeManager](../baseoverridethememanager), [NotesSlideThemeManager](../notesslidethememanager)

---

### hasDependingSlides {#hasDependingSlides}

| Όνομα | Περιγραφή |
| --- | --- |
| hasDependingSlides () | Επιστρέφει true εάν υπάρχει τουλάχιστον μία διαφάνεια που εξαρτάται από αυτή τη διάταξη διαφάνειας. Μόνο ανάγνωση boolean. |

**Επιστρέφει:**
boolean

---

### remove {#remove}

| Όνομα | Περιγραφή |
| --- | --- |
| remove () | Αφαιρεί τη διάταξη από την παρουσίαση. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| PptxEditException | Εκτυπώνεται αν η διάταξη έχει ήδη αφαιρεθεί από την παρουσίαση ή αν η διάταξη χρησιμοποιείται στην παρουσίαση (η ιδιότητα HasDependingSlides είναι true). Για να αποφύγετε την εκτόξευση του PptxEditException, ελέγξτε πρώτα την ιδιότητα HasDependingSlides της διάταξης. |

---

### setMasterSlide {#setMasterSlide}

| Όνομα | Περιγραφή |
| --- | --- |
| setMasterSlide ([MasterSlide](../masterslide)) | Επιστρέφει ή ορίζει τη κύρια διαφάνεια για μια διάταξη. Ανάγνωση/εγγραφή IMasterSlide. |

**Επιστρέφει:**
void

---

### setShowMasterShapes {#setShowMasterShapes}

| Όνομα | Περιγραφή |
| --- | --- |
| setShowMasterShapes (boolean) | Καθορίζει εάν τα σχήματα στην κύρια διαφάνεια πρέπει να εμφανίζονται στις διαφάνειες ή όχι. Ανάγνωση/εγγραφή boolean. |

**Επιστρέφει:**
void

---