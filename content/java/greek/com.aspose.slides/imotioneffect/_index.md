---
title: IMotionEffect
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τη συμπεριφορά του εφέ κίνησης.
type: docs
url: /el/com.aspose.slides/imotioneffect/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Αντιπροσωπεύει τη συμπεριφορά του εφέ κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFrom()](#getFrom--) | Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). |
| [getTo()](#getTo--) | Καθορίζει τη θέση προορισμού για ένα εφέ κίνησης (σε ποσοστά). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Καθορίζει τη θέση προορισμού για ένα εφέ κίνησης (σε ποσοστά). |
| [getBy()](#getBy--) | Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). |
| [getRotationCenter()](#getRotationCenter--) | Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή ενός μονοπατιού κίνησης κατά γωνία X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή ενός μονοπατιού κίνησης κατά γωνία X. |
| [getOrigin()](#getOrigin--) | Καθορίζει το σημείο προέλευσης του μονοπατιού κίνησης ως προς τη διάταξη της διαφάνειας ή το γονικό στοιχείο. |
| [setOrigin(int value)](#setOrigin-int-) | Καθορίζει το σημείο προέλευσης του μονοπατιού κίνησης ως προς τη διάταξη της διαφάνειας ή το γονικό στοιχείο. |
| [getPath()](#getPath--) | Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση του εφέ. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση του εφέ. |
| [getPathEditMode()](#getPathEditMode--) | Καθορίζει πώς κινείται το μονοπάτι κίνησης όταν μετακινείται το σχήμα. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Καθορίζει πώς κινείται το μονοπάτι κίνησης όταν μετακινείται το σχήμα. |
| [getAngle()](#getAngle--) | Περιγράφει τη σχετική γωνία του μονοπατιού κίνησης. |
| [setAngle(float value)](#setAngle-float-) | Περιγράφει τη σχετική γωνία του μονοπατιού κίνησης. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Καθορίζει τη θέση προορισμού για ένα εφέ κίνησης (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Καθορίζει τη θέση προορισμού για ένα εφέ κίνησης (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή ενός μονοπατιού κίνησης κατά γωνία X. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Επιστρέφει:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή ενός μονοπατιού κίνησης κατά γωνία X. Ανάγνωση/εγγραφή java.awt.geom.Point2D.Float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Καθορίζει το σημείο προέλευσης του μονοπατιού κίνησης ως προς τη διάταξη της διαφάνειας ή το γονικό στοιχείο. Ανάγνωση/εγγραφή [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Επιστρέφει:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Καθορίζει το σημείο προέλευσης του μονοπατιού κίνησης ως προς τη διάταξη της διαφάνειας ή το γονικό στοιχείο. Ανάγνωση/εγγραφή [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση του εφέ. Ανάγνωση/εγγραφή [IMotionPath](../../com.aspose.slides/imotionpath).

**Επιστρέφει:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση του εφέ. Ανάγνωση/εγγραφή [IMotionPath](../../com.aspose.slides/imotionpath).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Καθορίζει πώς κινείται το μονοπάτι κίνησης όταν μετακινείται το σχήμα. Ανάγνωση/εγγραφή [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Επιστρέφει:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Καθορίζει πώς κινείται το μονοπάτι κίνησης όταν μετακινείται το σχήμα. Ανάγνωση/εγγραφή [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Περιγράφει τη σχετική γωνία του μονοπατιού κίνησης. Ανάγνωση/εγγραφή float.

**Επιστρέφει:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Περιγράφει τη σχετική γωνία του μονοπατιού κίνησης. Ανάγνωση/εγγραφή float.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |