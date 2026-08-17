---
title: SlideShowTransition
second_title: Référence API Aspose.Slides pour Java
description: Représente la transition de diaporama.
type: docs
url: /fr/com.aspose.slides/slideshowtransition/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Représente la transition de diaporama.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSound()](#getSound--) | Renvoie ou définit les données audio intégrées. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Renvoie ou définit les données audio intégrées. |
| [getSoundMode()](#getSoundMode--) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [setSoundMode(int value)](#setSoundMode-int-) | Définit ou renvoie le mode son pour la transition de diapositive. |
| [getSoundLoop()](#getSoundLoop--) | Cet attribut spécifie si le son bouclera jusqu'au prochain événement sonore dans le diaporama. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Cet attribut spécifie si le son bouclera jusqu'au prochain événement sonore dans le diaporama. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Spécifie si un clic de souris fera avancer la diapositive ou non. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Spécifie si un clic de souris fera avancer la diapositive ou non. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. |
| [getSpeed()](#getSpeed--) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [setSpeed(int value)](#setSpeed-int-) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [getValue()](#getValue--) | Valeur de la transition du diaporama. |
| [getType()](#getType--) | Type de transition. |
| [setType(int value)](#setType-int-) | Type de transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Spécifie si ce son est intégré ou non. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Spécifie si ce son est intégré ou non. |
| [getSoundName()](#getSoundName--) | Spécifie un nom lisible pour le son de la transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Spécifie un nom lisible pour le son de la transition. |
| [getDuration()](#getDuration--) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
| [setDuration(int value)](#setDuration-int-) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si les deux instances de SlideShowTransition sont égales. |
| [hashCode()](#hashCode--) | Fournit une fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Renvoie ou définit les données audio intégrées. Lecture/écriture [IAudio](../../com.aspose.slides/iaudio).

**Renvoie :**
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

**Renvoie :**
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

Cet attribut spécifie si le son bouclera jusqu'au prochain événement sonore dans le diaporama. Lecture/écriture boolean.

**Renvoie :**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Cet attribut spécifie si le son bouclera jusqu'au prochain événement sonore dans le diaporama. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est supposée. Lecture/écriture boolean.

**Renvoie :**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est supposée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture boolean.

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenir la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Advance Slide After est coché
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenir la valeur du temps d'avance après la diapositive
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture boolean.

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Obtenir la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Advance Slide After est coché
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Obtenir la valeur du temps d'avance après la diapositive
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. Ce paramètre peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, aucun auto-avancement n'est supposé. Lecture/écriture long.

**Renvoie :**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. Ce paramètre peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, aucun auto-avancement n'est supposé. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture/écriture [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Renvoie :**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture/écriture [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Valeur de la transition du diaporama. Lecture seule [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Renvoie :**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Type de transition. Lecture/écriture [TransitionType](../../com.aspose.slides/transitiontype).

**Renvoie :**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Type de transition. Lecture/écriture [TransitionType](../../com.aspose.slides/transitiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Spécifie si ce son est intégré ou non. Si cet attribut est fixé à true, l'application génératrice est avertie de vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon le besoin. Lecture/écriture boolean.

**Renvoie :**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Spécifie si ce son est intégré ou non. Si cet attribut est fixé à true, l'application génératrice est avertie de vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon le besoin. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Spécifie un nom lisible pour le son de la transition. La propriété Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) doit être affectée pour obtenir ou définir le nom du son. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Spécifie un nom lisible pour le son de la transition. La propriété Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) doit être affectée pour obtenir ou définir le nom du son. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture/écriture int.

--------------------

Corresponds à l'attribut p14:dur de l'élément p:transition du schéma PresentationML. S'il n'est pas défini, la durée est déterminée automatiquement en fonction de la propriété \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) et du type de transition.

**Renvoie :**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture/écriture int.

--------------------

Corresponds à l'attribut p14:dur de l'élément p:transition du schéma PresentationML. S'il n'est pas défini, la durée est déterminée automatiquement en fonction de la propriété \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) et du type de transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si les deux instances de SlideShowTransition sont égales. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le SlideShowTransition à comparer avec le SlideShowTransition actuel. |

**Renvoie :**
boolean -  **true**  si le SlideShowTransition spécifié est égal au SlideShowTransition actuel ; sinon,  **false** .

### hashCode() {#hashCode--}
```
public int hashCode()
```

Fournit une fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.

**Renvoie :**
int - 23454

--------------------

Redéfini pour satisfaire le compilateur. Retourne toujours une constante car l'objet est mutable.