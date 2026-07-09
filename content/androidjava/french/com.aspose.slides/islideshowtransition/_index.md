---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la transition du diaporama.
type: docs
url: /fr/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Représente la transition du diaporama.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSound()](#getSound--) | Renvoie ou définit les données audio intégrées. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Renvoie ou définit les données audio intégrées. |
| [getSoundMode()](#getSoundMode--) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [setSoundMode(int value)](#setSoundMode-int-) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [getSoundLoop()](#getSoundLoop--) | Cet attribut spécifie si le son se répète jusqu'au prochain événement sonore dans le diaporama. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Cet attribut spécifie si le son se répète jusqu'au prochain événement sonore dans le diaporama. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Indique si un clic de souris fera avancer la diapositive ou non. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Indique si un clic de souris fera avancer la diapositive ou non. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. |
| [getSpeed()](#getSpeed--) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [setSpeed(int value)](#setSpeed-int-) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [getValue()](#getValue--) | Valeur de transition du diaporama. |
| [getType()](#getType--) | Type de transition. |
| [setType(int value)](#setType-int-) | Type de transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Indique si ce son est un son intégré ou non. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Indique si ce son est un son intégré ou non. |
| [getSoundName()](#getSoundName--) | Spécifie un nom lisible par l'homme pour le son de la transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Spécifie un nom lisible par l'homme pour le son de la transition. |
| [getDuration()](#getDuration--) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
| [setDuration(int value)](#setDuration-int-) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Renvoie ou définit les données audio intégrées. Lecture-écriture [IAudio](../../com.aspose.slides/iaudio).

**Renvoie :**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Renvoie ou définit les données audio intégrées. Lecture-écriture [IAudio](../../com.aspose.slides/iaudio).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```


Définit ou renvoie le mode son pour la transition de diapositive. Lecture-écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Renvoie :**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```


Définit ou renvoie le mode son pour la transition de diapositive. Lecture-écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```


Cet attribut spécifie si le son se répète jusqu'au prochain événement sonore dans le diaporama. Lecture-écriture booléen.

**Renvoie :**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```


Cet attribut spécifie si le son se répète jusqu'au prochain événement sonore dans le diaporama. Lecture-écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```


Indique si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est supposée. Lecture-écriture booléen.

**Renvoie :**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```


Indique si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est supposée. Lecture-écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```


Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture booléen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Get the first slide Transition
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Check if the Advance Slide After flag is checked
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Get the Advance Slide After Time value
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
public abstract void setAdvanceAfter(boolean value)
```
This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write  boolean .

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
>          // Obtenir la valeur du temps d'avance de la diapositive après
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public abstract long getAdvanceAfterTime()
```

Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read-write long.

**Returns:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Specifies the time, in milliseconds, after which the transition should start. This setting may be used in conjunction with the advClick attribute. If this attribute is not specified then it is assumed that no auto-advance will occur. Read-write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Returns:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Specifies the transition speed that is to be used when transitioning from the current slide to the next. Read-write [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Valeur de transition du diaporama. Lecture seule [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Renvoie:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Type of transition. Read-write [TransitionType](../../com.aspose.slides/transitiontype).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Type of transition. Read-write [TransitionType](../../com.aspose.slides/transitiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Returns:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```
Specifies whether or not this sound is a built-in sound. If this attribute is set to true then the generating application is alerted to check the name attribute specified for this sound in it's list of built-in sounds and can then surface a custom name or UI as needed. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Specifies a human readable name for the sound of the transition. The (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) property must be assigned to get or set the sound name. Read-write String.

**Returns:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Specifies a human readable name for the sound of the transition. The \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) property must be assigned to get or set the sound name. Read-write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Gets or sets the duration of the slide transition effect in milliseconds. Read/write int.

--------------------

Corresponds to the p14:dur attribute of the p:transition element in the PresentationML schema. If not set, the duration is determined automatically based on the \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) property and the transition type.

**Returns:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)


Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture/écriture int.

--------------------

Correspond à l'attribut p14:dur de l'élément p:transition dans le schéma PresentationML. S'il n'est pas défini, la durée est déterminée automatiquement en fonction de la propriété \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) et du type de transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |