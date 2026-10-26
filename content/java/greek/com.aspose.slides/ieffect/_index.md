---
title: IEffect
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά εφέ κίνησης.
type: docs
url: /el/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Αναπαριστά εφέ κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSequence()](#getSequence--) | Επιστρέφει μια ακολουθία για ένα εφέ. |
| [getTextAnimation()](#getTextAnimation--) | Επιστρέφει κίνηση κειμένου. |
| [getPresetClassType()](#getPresetClassType--) | Ορίζει τη κατηγορία του εφέ. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Ορίζει τη κατηγορία του εφέ. |
| [getType()](#getType--) | Ορίζει τον τύπο του εφέ. |
| [setType(int value)](#setType-int-) | Ορίζει τον τύπο του εφέ. |
| [getSubtype()](#getSubtype--) | Ορίζει τον υποτύπο του εφέ. |
| [setSubtype(int value)](#setSubtype-int-) | Ορίζει τον υποτύπο του εφέ. |
| [getBehaviors()](#getBehaviors--) | Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. |
| [getTiming()](#getTiming--) | Ορίζει την τιμή χρόνου για το εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Ορίζει την τιμή χρόνου για το εφέ. |
| [getTargetShape()](#getTargetShape--) | Επιστρέφει το σχήμα-στόχο για το εφέ. |
| [getSound()](#getSound--) | Ορίζει ενσωματωμένο ήχο για το εφέ. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Ορίζει ενσωματωμένο ήχο για το εφέ. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Ορίζει τύπο μετά-κίνησης για το εφέ. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Ορίζει τύπο μετά-κίνησης για το εφέ. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Ορίζει χρώμα μετά-κίνησης για το εφέ. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Ορίζει χρώμα μετά-κίνησης για το εφέ. |
| [getAnimateTextType()](#getAnimateTextType--) | Ορίζει τύπο κίνησης κειμένου για το εφέ. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Ορίζει τύπο κίνησης κειμένου για το εφέ. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Ορίζει καθυστέρηση μεταξύ τμημάτων κειμένου που κινούνται (λέξεις ή γράμματα). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Ορίζει καθυστέρηση μεταξύ τμημάτων κειμένου που κινούνται (λέξεις ή γράμματα). |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Επιστρέφει μια ακολουθία για ένα εφέ. Μόνο ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Επιστρέφει κίνηση κειμένου. Μόνο ανάγνωση [ITextAnimation](../../com.aspose.slides/itextanimation).

**Επιστρέφει:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Ορίζει τη κατηγορία του εφέ. Ανάγνωση/Εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Επιστρέφει:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Ορίζει τη κατηγορία του εφέ. Ανάγνωση/Εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Ορίζει τον τύπο του εφέ. Ανάγνωση/Εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Ορίζει τον τύπο του εφέ. Ανάγνωση/Εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Ορίζει τον υποτύπο του εφέ. Ανάγνωση/Εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Επιστρέφει:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Ορίζει τον υποτύπο του εφέ. Ανάγνωση/Εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. Ανάγνωση/Εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Επιστρέφει:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. Ανάγνωση/Εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Ορίζει την τιμή χρόνου για το εφέ. Ανάγνωση/Εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Ορίζει την τιμή χρόνου για το εφέ. Ανάγνωση/Εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Επιστρέφει το σχήμα-στόχο για το εφέ. Μόνο ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Ορίζει ενσωματωμένο ήχο για το εφέ. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λαμβάνει τη σειρά εφέ για τη διαφάνεια
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Εξάγει τον ήχο του εφέ σε πίνακα byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Ορίζει ενσωματωμένο ήχο για το εφέ. Ανάγνωση/Εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Λαμβάνει τη σειρά εφέ για τη διαφάνεια
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Εξάγει τον ήχο του εφέ σε πίνακα byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```

Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση/Εγγραφή  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Λαμβάνει το πρώτο εφέ της δεύτερης διαφάνειας.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Αλλάζει το δεύτερο εφέ Στοιχεία ενίσχυσης/Ήχος σε "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση/Εγγραφή  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Λαμβάνει το πρώτο εφέ της δεύτερης διαφάνειας.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Αλλάζει το δεύτερο εφέ Στοιχεία ενίσχυσης/Ήχος σε "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```

Ορίζει τύπο μετά-κίνησης για το εφέ. Ανάγνωση/Εγγραφή  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει το AfterAnimation του εφέ σε "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```

Ορίζει τύπο μετά-κίνησης για το εφέ. Ανάγνωση/Εγγραφή  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει το After animation του εφέ σε "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```

Ορίζει χρώμα μετά-κίνησης για το εφέ. Ανάγνωση/Εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο After animation του εφέ σε "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ορίζει το χρώμα After animation του εφέ.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```

Ορίζει χρώμα μετά-κίνησης για το εφέ. Ανάγνωση/Εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο After animation του εφέ σε "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ορίζει το χρώμα After animation του εφέ.
>      firstSlideEffect.getAfterAnimationColor().setColor(new java.awt.Color(0, 255, 0, 255));
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```

Ορίζει τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα μαζί. Ανάγνωση/Εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο Animate text του εφέ σε "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```

Ορίζει τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα μαζί. Ανάγνωση/Εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο Animate text του εφέ σε "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```

Ορίζει καθυστέρηση μεταξύ τμημάτων κειμένου που κινούνται (λέξεις ή γράμματα). Μία θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/Εγγραφή  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο Animate text του εφέ σε "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ορίζει την καθυστέρηση μεταξύ τμημάτων κειμένου που κινείται σε 20% της διάρκειας του εφέ.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Επιστρέφει:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```

Ορίζει καθυστέρηση μεταξύ τμημάτων κειμένου που κινούνται (λέξεις ή γράμματα). Μία θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/Εγγραφή  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο Animate text του εφέ σε "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ορίζει την καθυστέρηση μεταξύ τμημάτων κειμένου που κινείται σε 20% της διάρκειας του εφέ.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |