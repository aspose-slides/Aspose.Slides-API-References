---
title: TemplateContext
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεί μια διεπαφή αντικειμένου μοντέλου για μια μηχανή προτύπων.
type: docs
url: /el/com.aspose.slides/templatecontext/
---
**Κληρονομικότητα:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Αντιπροσωπεί μια διεπαφή αντικειμένου μοντέλου για μια μηχανή προτύπων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Δημιουργεί ένα παιδικό πλαίσιο προτύπου. |
| [getObject()](#getObject--) | Επιστρέφει το αντικείμενο μοντέλου. |
| [getOutput()](#getOutput--) | Επιστρέφει τη συλλογή των στοιχείων εξόδου του κεντρικού εγγράφου. |
| [getLocal()](#getLocal--) | Επιστρέφει την τοπική αποθήκευση του τρέχοντος πλαισίου προτύπου. |
| [getGlobal()](#getGlobal--) | Επιστρέφει την παγκόσμια αποθήκευση του κεντρικού εγγράφου. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Δημιουργεί ένα παιδικό πλαίσιο προτύπου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| subModel | TSubModel | Αντικείμενο παιδικού μοντέλου. |

**Επιστρέφει:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Νέο πλαίσιο προτύπου με το δοσμένο μοντέλο και τη συλλογή εξόδου του γονέα και την παγκόσμια αποθήκευση.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Επιστρέφει το αντικείμενο μοντέλου. Μόνο για ανάγνωση Object.

**Επιστρέφει:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Επιστρέφει τη συλλογή των στοιχείων εξόδου του κεντρικού εγγράφου. Μόνο για ανάγνωση [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Επιστρέφει:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Επιστρέφει την τοπική αποθήκευση του τρέχοντος πλαισίου προτύπου. Μόνο για ανάγνωση [Storage](../../com.aspose.slides/storage).

**Επιστρέφει:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Επιστρέφει την παγκόσμια αποθήκευση του κεντρικού εγγράφου. Μόνο για ανάγνωση [Storage](../../com.aspose.slides/storage).

**Επιστρέφει:**
[Storage](../../com.aspose.slides/storage)