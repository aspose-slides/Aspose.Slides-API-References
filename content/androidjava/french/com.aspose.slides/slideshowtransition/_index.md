---
title: SlideShowTransition
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente la transition du diaporama.
type: docs
url: /fr/com.aspose.slides/slideshowtransition/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Représente la transition du diaporama.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSound()](#getSound--) | Renvoie ou définit les données audio intégrées. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Renvoie ou définit les données audio intégrées. |
| [getSoundMode()](#getSoundMode--) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [setSoundMode(int value)](#setSoundMode-int-) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [getSoundLoop()](#getSoundLoop--) | Cet attribut indique si le son doit boucler jusqu’au prochain événement sonore du diaporama. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Cet attribut indique si le son doit boucler jusqu’au prochain événement sonore du diaporama. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Indique si un clic de souris fera avancer la diapositive ou non. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Indique si un clic de souris fera avancer la diapositive ou non. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Indique le temps, en millisecondes, après lequel la transition doit commencer. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Indique le temps, en millisecondes, après lequel la transition doit commencer. |
| [getSpeed()](#getSpeed--) | Indique la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [setSpeed(int value)](#setSpeed-int-) | Indique la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [getValue()](#getValue--) | Valeur de transition du diaporama. |
| [getType()](#getType--) | Type de transition. |
| [setType(int value)](#setType-int-) | Type de transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Indique si ce son est intégré ou non. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Indique si ce son est intégré ou non. |
| [getSoundName()](#getSoundName--) | Définit un nom lisible par l’homme pour le son de la transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Définit un nom lisible par l’homme pour le son de la transition. |
| [getDuration()](#getDuration--) | Obtient ou définit la durée de l’effet de transition de diapositive en millisecondes. |
| [setDuration(int value)](#setDuration-int-) | Obtient ou définit la durée de l’effet de transition de diapositive en millisecondes. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si les deux instances de SlideShowTransition sont égales. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Renvoie ou définit les données audio intégrées. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Retour :**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Renvoie ou définit les données audio intégrées. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Définit ou renvoie le mode son pour la transition de diapositive. Lecture/écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retour :**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Définit ou renvoie le mode son pour la transition de diapositive. Lecture/écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Cet attribut indique si le son doit boucler jusqu’au prochain événement sonore du diaporama. Lecture/écriture boolean.

**Retour :**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Cet attribut indique si le son doit boucler jusqu’au prochain événement sonore du diaporama. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Indique si un clic de souris fera avancer la diapositive ou non. Si cet attribut n’est pas spécifié, la valeur true est supposée. Lecture/écriture boolean.

**Retour :**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Indique si un clic de souris fera avancer la diapositive ou non. Si cet attribut n’est pas spécifié, la valeur true est supposée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenir la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Avancer la diapositive après est activé
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenir la valeur du temps d'avancement après la diapositive
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenir la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Avancer la diapositive après est activé
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenir la valeur du temps d'avancement après la diapositive
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long.

**Returns:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returns:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read/write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Slide show transition value. Read-only [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Returns:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public final int getType()
```

Type of transition. Read/write [TransitionType](../../com.aspose.slides/transitiontype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Type of transition. Read/write [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Returns:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Specifies a human readable name for the sound of the transition. The  Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String.

**Returns:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Specifies a human readable name for the sound of the transition. The  Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Gets or sets the duration of the slide transition effect in milliseconds. Read/write int.

--------------------

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**Returns:**
int
### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Gets or sets the duration of the slide transition effect in milliseconds. Read/write int.

--------------------

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si les deux instances de SlideShowTransition sont égales. Lecture/écriture booléen.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le SlideShowTransition à comparer avec le SlideShowTransition actuel. |

**Retour :**
booléen -  **true**  si le SlideShowTransition spécifié est égal au SlideShowTransition actuel ; sinon,  **false** .
### hashCode() {#hashCode--}
```
public int hashCode()


Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Retour :**
int - 23454

--------------------

Surchargé pour satisfaire le compilateur. Retourne toujours une constante car l’objet est mutable.