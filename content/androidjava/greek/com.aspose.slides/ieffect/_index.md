---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
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
| [getPresetClassType()](#getPresetClassType--) | Καθορίζει την κλάση του εφέ. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Καθορίζει την κλάση του εφέ. |
| [getType()](#getType--) | Καθορίζει τον τύπο του εφέ. |
| [setType(int value)](#setType-int-) | Καθορίζει τον τύπο του εφέ. |
| [getSubtype()](#getSubtype--) | Καθορίζει το υποτύπο του εφέ. |
| [setSubtype(int value)](#setSubtype-int-) | Καθορίζει το υποτύπο του εφέ. |
| [getBehaviors()](#getBehaviors--) | Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. |
| [getTiming()](#getTiming--) | Καθορίζει την τιμή χρονομέτρησης για το εφέ. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Καθορίζει την τιμή χρονομέτρησης για το εφέ. |
| [getTargetShape()](#getTargetShape--) | Επιστρέφει το σχήμα-στόχο για το εφέ. |
| [getSound()](#getSound--) | Καθορίζεται ενσωματωμένος ήχος για το εφέ. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Καθορίζεται ενσωματωμένος ήχος για το εφέ. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Καθορίζεται τύπος μετά-ανίμασης για το εφέ. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Καθορίζεται τύπος μετά-ανίμασης για το εφέ. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Καθορίζεται χρώμα μετά-ανίμασης για το εφέ. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Καθορίζεται χρώμα μετά-ανίμασης για το εφέ. |
| [getAnimateTextType()](#getAnimateTextType--) | Καθορίζει τύπο κίνησης κειμένου για το εφέ. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Καθορίζει τύπο κίνησης κειμένου για το εφέ. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Καθορίζει καθυστέρηση μεταξύ τμημάτων κειμένου κίνησης (λέξεις ή γράμματα). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Καθορίζει καθυστέρηση μεταξύ τμημάτων κειμένου κίνησης (λέξεις ή γράμματα). |

### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```

Επιστρέφει μια ακολουθία για ένα εφέ. Μόνο για ανάγνωση [ISequence](../../com.aspose.slides/isequence).

**Επιστρέφει:**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```

Επιστρέφει κίνηση κειμένου. Μόνο για ανάγνωση [ITextAnimation](../../com.aspose.slides/itextanimation).

**Επιστρέφει:**
[ITextAnimation](../../com.aspose.slides/itextanimation)

### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```

Καθορίζει την κλάση του εφέ. Ανάγνωση/εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Επιστρέφει:**
int

### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```

Καθορίζει την κλάση του εφέ. Ανάγνωση/εγγραφή [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

Καθορίζει τον τύπο του εφέ. Ανάγνωση/εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Επιστρέφει:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Καθορίζει τον τύπο του εφέ. Ανάγνωση/εγγραφή [EffectType](../../com.aspose.slides/effecttype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```

Καθορίζει το υποτύπο του εφέ. Ανάγνωση/εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Επιστρέφει:**
int

### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```

Καθορίζει το υποτύπο του εφέ. Ανάγνωση/εγγραφή [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```

Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. Ανάγνωση/εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Επιστρέφει:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)

### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```

Επιστρέφει τη συλλογή συμπεριφορών για το εφέ. Ανάγνωση/εγγραφή [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Καθορίζει την τιμή χρονομέτρησης για το εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Επιστρέφει:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Καθορίζει την τιμή χρονομέτρησης για το εφέ. Ανάγνωση/εγγραφή [ITiming](../../com.aspose.slides/itiming).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```

Επιστρέφει το σχήμα-στόχο για το εφέ. Μόνο για ανάγνωση [IShape](../../com.aspose.slides/ishape).

**Επιστρέφει:**
[IShape](../../com.aspose.slides/ishape)

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Καθορίζεται ενσωματωμένος ήχος για το εφέ. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
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

Καθορίζεται ενσωματωμένος ήχος για το εφέ. Ανάγνωση/εγγραφή [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Gets the effects sequence for the slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Extracts the effect sound in byte array
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

Αυτό το χαρακτηριστικό καθορίζει αν το εφέ κίνησης σταματά τον προηγούμενο ήχο. Ανάγνωση/εγγραφή  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Get the first effect of the second slide.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Change the second effect Enhancements/Sound to "Stop Previous Sound"
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
>          // Αλλάζει το ήχο του δεύτερου εφέ σε "Stop Previous Sound"
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

Καθορίζεται τύπος μετά-ανίμασης για το εφέ. Ανάγνωση/εγγραφή  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει το μετά-ανίμαση του εφέ σε "Hide on Next Mouse Click"
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

Καθορίζεται τύπος μετά-ανίμασης για το εφέ. Ανάγνωση/εγγραφή  AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect After animation to "Hide on Next Mouse Click"
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

Καθορίζεται χρώμα μετά-ανίμασης για το εφέ. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο μετά-ανίμασης του εφέ σε "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ορίζει το χρώμα μετά-ανίμασης του εφέ.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
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

Καθορίζεται χρώμα μετά-ανίμασης για το εφέ. Ανάγνωση/εγγραφή [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο μετά-ανίμασης του εφέ σε "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Ορίζει το χρώμα μετά-ανίμασης του εφέ.
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
public abstract int getAnimateTextType()
```

Καθορίζει τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να αναπαράγεται γράμμα-γράμμα, λέξη-λεξιακά ή ολόκληρο ταυτόχρονα. Ανάγνωση/εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο κίνησης κειμένου του εφέ σε "By letter"
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

Καθορίζει τύπο κίνησης κειμένου για το εφέ. Το κείμενο του σχήματος μπορεί να αναπαράγεται γράμμα-γράμμα, λέξη-λεξιακά ή ολόκληρο ταυτόχρονα. Ανάγνωση/εγγραφή  AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο κίνησης κειμένου του εφέ σε "By letter"
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

Καθορίζει καθυστέρηση μεταξύ τμημάτων κειμένου κίνησης (λέξεις ή γράμματα). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/εγγραφή  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Λαμβάνει το πρώτο εφέ της πρώτης διαφάνειας.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Αλλάζει τον τύπο κίνησης κειμένου του εφέ σε "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Ορίζει την καθυστέρηση μεταξύ τμημάτων κειμένου κίνησης στο 20% της διάρκειας του εφέ.
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

Καθορίζει καθυστέρηση μεταξύ τμημάτων κειμένου κίνησης (λέξεις ή γράμματα). Μια θετική τιμή καθορίζει το ποσοστό της διάρκειας του εφέ. Μια αρνητική τιμή καθορίζει την καθυστέρηση σε δευτερόλεπτα. Ανάγνωση/εγγραφή  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Get the first effect of the first slide.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Change the effect Animate text type to "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Set the delay between animated text parts to 20% of effect duration.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | float |  |