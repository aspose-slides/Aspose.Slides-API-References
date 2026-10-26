---
title: ISmartArt
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αναπαριστά ένα διάγραμμα SmartArt.
type: docs
url: /el/com.aspose.slides/ismartart/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Αναπαριστά ένα διάγραμμα SmartArt.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Επιστρέφει συλλογές όλων των κόμβων στο αντικείμενο SmartArt. |
| [getNodes()](#getNodes--) | Επιστρέφει συλλογές των ριζικών κόμβων στο αντικείμενο SmartArt. |
| [getLayout()](#getLayout--) | Επιστρέφει ή ορίζει τη διάταξη του αντικειμένου SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Επιστρέφει ή ορίζει τη διάταξη του αντικειμένου SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Επιστρέφει ή ορίζει το γρήγορο στυλ του αντικειμένου SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Επιστρέφει ή ορίζει το γρήγορο στυλ του αντικειμένου SmartArt. |
| [getColorStyle()](#getColorStyle--) | Επιστρέφει ή ορίζει το στυλ χρώματος του αντικειμένου SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Επιστρέφει ή ορίζει το στυλ χρώματος του αντικειμένου SmartArt. |
| [isReversed()](#isReversed--) | Επιστρέφει ή ορίζει την κατάσταση του διαγράμματος SmartArt σχετικά με (αριστερό-προς-δεξιά) LTR ή (δεξιό-προς-αριστερά) RTL, εάν το διάγραμμα υποστηρίζει αναστροφή. |
| [setReversed(boolean value)](#setReversed-boolean-) | Επιστρέφει ή ορίζει την κατάσταση του διαγράμματος SmartArt σχετικά με (αριστερό-προς-δεξιά) LTR ή (δεξιό-προς-αριστερά) RTL, εάν το διάγραμμα υποστηρίζει αναστροφή. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Επιστρέφει συλλογές όλων των κόμβων στο αντικείμενο SmartArt. Μόνο για ανάγνωση [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Επιστρέφει:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Επιστρέφει συλλογές των ριζικών κόμβων στο αντικείμενο SmartArt. Μόνο για ανάγνωση [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Επιστρέφει:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Επιστρέφει ή ορίζει τη διάταξη του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Επιστρέφει:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Επιστρέφει ή ορίζει τη διάταξη του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Επιστρέφει ή ορίζει το γρήγορο στυλ του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Επιστρέφει:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Επιστρέφει ή ορίζει το γρήγορο στυλ του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Επιστρέφει ή ορίζει το στυλ χρώματος του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Επιστρέφει:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Επιστρέφει ή ορίζει το στυλ χρώματος του αντικειμένου SmartArt. Ανάγνωση/εγγραφή [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Επιστρέφει ή ορίζει την κατάσταση του διαγράμματος SmartArt σχετικά με (αριστερό-προς-δεξιά) LTR ή (δεξιό-προς-αριστερά) RTL, εάν το διάγραμμα υποστηρίζει αναστροφή. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Επιστρέφει ή ορίζει την κατάσταση του διαγράμματος SmartArt σχετικά με (αριστερό-προς-δεξιά) LTR ή (δεξιό-προς-αριστερά) RTL, εάν το διάγραμμα υποστηρίζει αναστροφή. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |