---
title: IMotionEffect
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αναπαριστά τη συμπεριφορά του εφέ κίνησης.
type: docs
url: /el/com.aspose.slides/imotioneffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Represent motion effect behavior of effect.
## Methods

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). |
| [getTo()](#getTo--) | Καθορίζει τη θέση-στόχο για ένα εφέ κίνησης (σε ποσοστά). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Καθορίζει τη θέση-στόχο για ένα εφέ κίνησης (σε ποσοστά). |
| [getBy()](#getBy--) | Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). |
| [getRotationCenter()](#getRotationCenter--) | Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή μιας διαδρομής κίνησης κατά γωνία X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή μιας διαδρομής κίνησης κατά γωνία X. |
| [getOrigin()](#getOrigin--) | Καθορίζει ποια είναι η προέλευση της διαδρομής κίνησης σε σχέση με κάτι όπως η διάταξη της διαφάνειας ή ο γονέας. |
| [setOrigin(int value)](#setOrigin-int-) | Καθορίζει ποια είναι η προέλευση της διαδρομής κίνησης σε σχέση με κάτι όπως η διάταξη της διαφάνειας ή ο γονέας. |
| [getPath()](#getPath--) | Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση. |
| [getPathEditMode()](#getPathEditMode--) | Καθορίζει πώς κινείται η διαδρομή κίνησης όταν μετακινείται το σχήμα. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Καθορίζει πώς κινείται η διαδρομή κίνησης όταν μετακινείται το σχήμα. |
| [getAngle()](#getAngle--) | Περιγράφει τη σχετική γωνία της διαδρομής κίνησης. |
| [setAngle(float value)](#setAngle-float-) | Περιγράφει τη σχετική γωνία της διαδρομής κίνησης. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Καθορίζει μια συντεταγμένη x/y από την οποία ξεκινά η κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Καθορίζει τη θέση-στόχο για ένα εφέ κίνησης (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Καθορίζει τη θέση-στόχο για ένα εφέ κίνησης (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Περιγράφει τη σχετική τιμή μετατόπισης για την κίνηση (σε ποσοστά). Ανάγνωση/εγγραφή android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή μιας διαδρομής κίνησης κατά γωνία X. Ανάγνωση/εγγραφή android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Περιγράφει το κέντρο περιστροφής που χρησιμοποιείται για την περιστροφή μιας διαδρομής κίνησης κατά γωνία X. Ανάγνωση/εγγραφή android.graphics.PointF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Καθορίζει ποια είναι η προέλευση της διαδρομής κίνησης σε σχέση με κάτι όπως η διάταξη της διαφάνειας ή ο γονέας. Ανάγνωση/εγγραφή [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Returns:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Καθορίζει ποια είναι η προέλευση της διαδρομής κίνησης σε σχέση με κάτι όπως η διάταξη της διαφάνειας ή ο γονέας. Ανάγνωση/εγγραφή [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση. Ανάγνωση/εγγραφή [IMotionPath](../../com.aspose.slides/imotionpath).

**Returns:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Καθορίζει το στοιχείο διαδρομής ακολουθούμενο από συντεταγμένες για την κίνηση. Ανάγνωση/εγγραφή [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Καθορίζει πώς κινείται η διαδρομή κίνησης όταν μετακινείται το σχήμα. Ανάγνωση/εγγραφή [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Returns:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Καθορίζει πώς κινείται η διαδρομή κίνησης όταν μετακινείται το σχήμα. Ανάγνωση/εγγραφή [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Περιγράφει τη σχετική γωνία της διαδρομής κίνησης. Ανάγνωση/εγγραφή float.

**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Περιγράφει τη σχετική γωνία της διαδρομής κίνησης. Ανάγνωση/εγγραφή float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |