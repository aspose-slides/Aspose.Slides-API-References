---
title: Effect
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά εφέ κίνησης.
type: docs
url: /el/com.aspose.slides/effect/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IEffect](../../com.aspose.slides/ieffect), com.aspose.slides.IDOMObject
```
public class Effect implements IEffect, IDOMObject
```

Αναπαριστά εφέ κίνησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSequence()](#getSequence--) | Επιστρέφει μια ακολουθία για ένα εφέ. |
| [getTextAnimation()](#getTextAnimation--) | TextAnimation Μόνο για ανάγνωση [ITextAnimation](../../com.aspose.slides/itextanimation). |
| [getPresetClassType()](#getPresetClassType--) | Ορίζει την κλάση του εφέ. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Ορίζει την κλάση του εφέ. |
| [getType()](#getType--) | Ορίζει τον τύπο του εφέ. |
| [setType(int value)](#setType-int-) | Ορίζει τον τύπο του εφέ. |
| [getSubtype()](#getSubtype--) | Ορίζει το υποτύπο του εφέ. |
| [setSubtype(int value)](#setSubtype-int-) | Ορίζει το υποτύπο του εφέ. |
| [getBehaviors()](#getBehaviors--) | Επιστρέφει τη συλλογή συμπεριφοράς για το εφέ. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Επιστρέφει τη συλλογή συμπεριφοράς για το εφέ. |
| [getTiming()](#getTiming--) | Ορίζει την τιμή χρονισμού για το εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Ορίζει την τιμή χρονισμού για το εφέ. |
| [getTargetShape()](#getTargetShape--) | Επιστρέφει το σχήμα-στόχο για το εφέ. |
| [getSound()](#getSound--) | Καθορίζει ενσωματωμένο ήχο για το εφέ. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Καθορίζει ενσωματωμένο ήχο για το εφέ. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Ορίζει έναν τύπο μετά την κίνηση για το εφέ. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Ορίζει έναν τύπο μετά την κίνηση για το εφέ. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Ορίζει ένα χρώμα μετά την κίνηση για το εφέ. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Ορίζει ένα χρώμα μετά την κίνηση για το εφέ. |
| [getAnimateTextType()](#getAnimateTextType--) | Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Ορίζει μια καθυστέρηση μεταξύ των τμημάτων του κινούμενου κειμένου (λέξεων ή γραμμάτων). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Ορίζει μια καθυστέρηση μεταξύ των τμημάτων του κινούμενου κειμένου (λέξεων ή γραμμάτων). |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getSequence() {#getSequence--}
```
public final ISequence getSequence()
```

Επιστρέφει μια ακολουθία για ένα εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public final ITextAnimation getTextAnimation()
```

TextAnimation Μόνο για ανάγνωση [ITextAnimation](../../com.aspose.slides/itextanimation).

**Επιστρέφει:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public final int getPresetClassType()
```

Ορίζει την κλάση του εφέ. Ανάγνωση/εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Επιστρέφει:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public final void setPresetClassType(int value)
```

Ορίζει την κλάση του εφέ. Ανάγνωση/εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public final int getType()
```

Ορίζει τον τύπο του εφέ. Ανάγνωση/εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Επιστρέφει:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Ορίζει τον τύπο του εφέ. Ανάγνωση/εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public final int getSubtype()
```

Ορίζει το υποτύπο του εφέ. Ανάγνωση/εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Επιστρέφει:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public final void setSubtype(int value)
```

Ορίζει το υποτύπο του εφέ. Ανάγνωση/εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public final IBehaviorCollection getBehaviors()
```

Επιστρέφει τη συλλογή συμπεριφοράς για το εφέ. Ανάγνωση/εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Επιστρέφει:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public final void setBehaviors(IBehaviorCollection value)
```

Επιστρέφει τη συλλογή συμπεριφοράς για το εφέ. Ανάγνωση/εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Ορίζει την τιμή χρονισμού για το εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Ορίζει την τιμή χρονισμού για το εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public final IShape getTargetShape()
```

Επιστρέφει το σχήμα-στόχο για το εφέ. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Καθορίζει ενσωματωμένο ήχο για το εφέ. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

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
public final void setSound(IAudio value)
```

Καθορίζει ενσωματωμένο ήχο για το εφέ. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

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
public final boolean getStopPreviousSound()
```

Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση/εγγραφή  boolean .

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
>          // Αλλάζει το Enhancements/Sound του δεύτερου εφέ σε "Stop Previous Sound"
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
public final void setStopPreviousSound(boolean value)
```

Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση/εγγραφή  boolean .

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
>          // Αλλάζει το Enhancements/Sound του δεύτερου εφέ σε "Stop Previous Sound"
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
public final int getAfterAnimationType()
```

Ορίζει έναν τύπο μετά την κίνηση για το εφέ. Ανάγνωση/εγγραφή [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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

**Επιστρέφει:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public final void setAfterAnimationType(int value)
```

Ορίζει έναν τύπο μετά την κίνηση για το εφέ. Ανάγνωση/εγγραφή [AfterAnimationType](../../com.aspose.slides/afteranimationtype)(\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

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
public final IColorFormat getAfterAnimationColor()
```

Ορίζει ένα χρώμα μετά την κίνηση για το εφέ. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public final void setAfterAnimationColor(IColorFormat value)
```

Ορίζει ένα χρώμα μετά την κίνηση για το εφέ. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

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
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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
public final int getAnimateTextType()
```

Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα ταυτόχρονα. Ανάγνωση/εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
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
public final void setAnimateTextType(int value)
```

Ορίζει έναν τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να κινείται ανά γράμμα, ανά λέξη ή όλα ταυτόχρονα. Ανάγνωση/εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
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
public final float getDelayBetweenTextParts()
```

Ορίζει μια καθυστέρηση μεταξύ τμημάτων του κινούμενου κειμένου (λέξεων ή γραμμάτων). Μία θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/εγγραφή  float .

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
>      // Ορίζει την καθυστέρηση μεταξύ των τμημάτων του κινούμενου κειμένου σε 20% της διάρκειας του εφέ.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Επιστρέφει:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public final void setDelayBetweenTextParts(float value)
```

Ορίζει μια καθυστέρηση μεταξύ τμημάτων του κινούμενου κειμένου (λέξεων ή γραμμάτων). Μία θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μία αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/εγγραφή  float .

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
>      // Ορίζει την καθυστέρηση μεταξύ των τμημάτων του κινούμενου κειμένου σε 20% της διάρκειας του εφέ.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Επιστρέφει το αντικείμενο Parent_Immediate. Μόνο για ανάγνωση IDOMObject.

**Επιστρέφει:**
com.aspose.slides.IDOMObject