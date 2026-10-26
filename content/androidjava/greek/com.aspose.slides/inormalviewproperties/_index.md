---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /el/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Αναπαριστά τις ιδιότητες της κανονικής προβολής. Η κανονική προβολή αποτελείται από τρεις περιοχές περιεχομένου: τη διαφάνεια αυτή καθαυτή, μια πλευρική περιοχή περιεχομένου και μια κάτω περιοχή περιεχομένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Specifies whether the application should show icons if displaying outline content in any of the content regions of normal view mode. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Specifies whether the vertical splitter should snap to a minimized state when the side region is sufficiently small. |
| [getVerticalBarState()](#getVerticalBarState--) | Specifies the state that the vertical splitter bar should be shown in. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Specifies the state that the vertical splitter bar should be shown in. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Specifies the state that the horizontal splitter bar should be shown in. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Specifies the state that the horizontal splitter bar should be shown in. |
| [getPreferSingleView()](#getPreferSingleView--) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Specifies whether the user prefers to see a full-window single-content region over the standard normal view with three content regions. |
| [getRestoredLeft()](#getRestoredLeft--) | This element specifies the sizing of the side content region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
| [getRestoredTop()](#getRestoredTop--) | This element specifies the sizing of the top slide region of the normal view, when the region is of a variable restored size(neither minimized nor maximized). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Καθορίζει εάν η εφαρμογή πρέπει να εμφανίζει εικονίδια όταν εμφανίζει περιεχόμενο περιγράμματος σε οποιαδήποτε από τις περιοχές περιεχομένου της λειτουργίας κανονικής προβολής. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να κλειδώνει σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Καθορίζει εάν ο κάθετος διαχωριστής πρέπει να κλειδώνει σε κατάσταση ελαχιστοποίησης όταν η πλευρική περιοχή είναι επαρκώς μικρή. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετος διαχωριστής. Ένας κάθετος διαχωριστής χωρίζει τη διαφάνεια από τη πλευρική περιοχή περιεχομένου.

**Επιστρέφει:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται η κάθετος διαχωριστής. Ένας κάθετος διαχωριστής χωρίζει τη διαφάνεια από τη πλευρική περιοχή περιεχομένου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται ο οριζόντιος διαχωριστής. Ένας οριζόντιος διαχωριστής χωρίζει τη διαφάνεια από την περιοχή περιεχομένου κάτω από τη διαφάνεια.

**Επιστρέφει:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Καθορίζει την κατάσταση στην οποία πρέπει να εμφανίζεται ο οριζόντιος διαχωριστής. Ένας οριζόντιος διαχωριστής χωρίζει τη διαφάνεια από την περιοχή περιεχομένου κάτω από τη διαφάνεια.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Καθορίζει εάν ο χρήστης προτιμά να δει μια μονή περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. Εάν ενεργοποιηθεί, η εφαρμογή ενδέχεται να επιλέξει να εμφανίσει μία από τις περιοχές περιεχομένου σε όλο το παράθυρο. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Καθορίζει εάν ο χρήστης προτιμά να δει μια μονή περιοχή περιεχομένου πλήρους παραθύρου αντί για την τυπική κανονική προβολή με τρεις περιοχές περιεχομένου. Εάν ενεργοποιηθεί, η εφαρμογή ενδέχεται να επιλέξει να εμφανίσει μία από τις περιοχές περιεχομένου σε όλο το παράθυρο. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Αυτό το στοιχείο καθορίζει το μέγεθος της πλευρικής περιοχής περιεχομένου της κανονικής προβολής, όταν η περιοχή έχει μεταβλητό επαναφερθέν μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). Μόνο για ανάγνωση [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Επιστρέφει:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Αυτό το στοιχείο καθορίζει το μέγεθος της κορυφαίας περιοχής διαφάνειας της κανονικής προβολής, όταν η περιοχή έχει μεταβλητό επαναφερθέν μέγεθος (ούτε ελαχιστοποιημένη ούτε μεγιστοποιημένη). Μόνο για ανάγνωση [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Επιστρέφει:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)