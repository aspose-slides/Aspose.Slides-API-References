---
title: IPropertyEffect
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αναπαριστά τη συμπεριφορά του εφέ ιδιότητας.
type: docs
url: /el/com.aspose.slides/ipropertyeffect/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

Αναπαριστά τη συμπεριφορά του εφέ ιδιότητας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFrom()](#getFrom--) | Καθορίζει την αρχική τιμή του animation. |
| [setFrom(String value)](#setFrom-java.lang.String-) | Καθορίζει την αρχική τιμή του animation. |
| [getTo()](#getTo--) | Καθορίζει την τελική τιμή για το animation. |
| [setTo(String value)](#setTo-java.lang.String-) | Καθορίζει την τελική τιμή για το animation. |
| [getBy()](#getBy--) | Καθορίζει μια σχετική τιμή μετατόπισης για το animation σε σχέση με τη θέση του πριν από την εκκίνηση του animation. |
| [setBy(String value)](#setBy-java.lang.String-) | Καθορίζει μια σχετική τιμή μετατόπισης για το animation σε σχέση με τη θέση του πριν από την εκκίνηση του animation. |
| [getValueType()](#getValueType--) | Καθορίζει τον τύπο μιας τιμής ιδιότητας. |
| [setValueType(int value)](#setValueType-int-) | Καθορίζει τον τύπο μιας τιμής ιδιότητας. |
| [getCalcMode()](#getCalcMode--) | Καθορίζει τη λειτουργία παρεμβολής για το animation Ανάγνωση/εγγραφή [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | Καθορίζει τη λειτουργία παρεμβολής για το animation Ανάγνωση/εγγραφή [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | Καθορίζει τα σημεία του animation. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | Καθορίζει τα σημεία του animation. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

Καθορίζει την αρχική τιμή του animation. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

Καθορίζει την αρχική τιμή του animation. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getTo() {#getTo--}
```
public abstract String getTo()
```

Καθορίζει την τελική τιμή για το animation. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

Καθορίζει την τελική τιμή για το animation. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getBy() {#getBy--}
```
public abstract String getBy()
```

Καθορίζει μια σχετική τιμή μετατόπισης για το animation σε σχέση με τη θέση του πριν από την εκκίνηση του animation. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

Καθορίζει μια σχετική τιμή μετατόπισης για το animation σε σχέση με τη θέση του πριν από την εκκίνηση του animation. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Καθορίζει τον τύπο μιας τιμής ιδιότητας. Ανάγνωση/εγγραφή [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Επιστρέφει:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Καθορίζει τον τύπο μιας τιμής ιδιότητας. Ανάγνωση/εγγραφή [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

Καθορίζει τη λειτουργία παρεμβολής για το animation Ανάγνωση/εγγραφή [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Επιστρέφει:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

Καθορίζει τη λειτουργία παρεμβολής για το animation Ανάγνωση/εγγραφή [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

Καθορίζει τα σημεία του animation. Ανάγνωση/εγγραφή [IPointCollection](../../com.aspose.slides/ipointcollection).

**Επιστρέφει:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

Καθορίζει τα σημεία του animation. Ανάγνωση/εγγραφή [IPointCollection](../../com.aspose.slides/ipointcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |