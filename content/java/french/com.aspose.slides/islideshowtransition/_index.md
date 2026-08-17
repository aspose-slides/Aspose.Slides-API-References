---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: Représente la transition du diaporama.
type: docs
url: /fr/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Représente la transition du diaporama.
## Methods

| Méthode | Description |
| --- | --- |
| [getSound()](#getSound--) | Renvoie ou définit les données audio intégrées. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Renvoie ou définit les données audio intégrées. |
| [getSoundMode()](#getSoundMode--) | Définit ou renvoie le mode son pour la transition du diaporama. |
| [setSoundMode(int value)](#setSoundMode-int-) | Définit ou renvoie le mode son pour la transition du diaporama. |
| [getSoundLoop()](#getSoundLoop--) | Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Spécifie si un clic de souris fera avancer la diapositive ou non. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Spécifie si un clic de souris fera avancer la diapositive ou non. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Spécifie le temps, en millisecondes, après lequel la transition doit commencer. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Spécifie le temps, en millisecondes, après lequel la transition doit commencer. |
| [getSpeed()](#getSpeed--) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [setSpeed(int value)](#setSpeed-int-) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. |
| [getValue()](#getValue--) | Valeur de transition du diaporama. |
| [getType()](#getType--) | Type de transition. |
| [setType(int value)](#setType-int-) | Type de transition. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Spécifie si ce son est un son intégré ou non. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Spécifie si ce son est un son intégré ou non. |
| [getSoundName()](#getSoundName--) | Spécifie un nom lisible par l'homme pour le son de la transition. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Spécifie un nom lisible par l'homme pour le son de la transition. |
| [getDuration()](#getDuration--) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
| [setDuration(int value)](#setDuration-int-) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Renvoie ou définit les données audio intégrées. Lecture-écriture [IAudio](../../com.aspose.slides/iaudio).

**Retour :**
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

Définit ou renvoie le mode son pour la transition du diaporama. Lecture-écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Retour :**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Définit ou renvoie le mode son pour la transition du diaporama. Lecture-écriture [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. Lecture-écriture booléen.

**Retour :**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. Lecture-écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est alors considérée. Lecture-écriture booléen.

**Retour :**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est alors considérée. Lecture-écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. Lecture-écriture booléen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Récupérer la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Avancer la diapositive après est activé
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Récupérer la valeur du temps d'avance après la diapositive
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour :**
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps. Lecture-écriture booléen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Récupérer la première transition de diapositive
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Vérifier si le drapeau Avancer la diapositive après est activé
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Récupérer la valeur du temps d'avance après la diapositive
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
public abstract long getAdvanceAfterTime()
```

Spécifie le temps, en millisecondes, après lequel la transition doit commencer. Ce paramètre peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, on considère qu'aucune avancée automatique ne se produira. Lecture-écriture long.

**Retour :**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Spécifie le temps, en millisecondes, après lequel la transition doit commencer. Ce paramètre peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, on considère qu'aucune avancée automatique ne se produira. Lecture-écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture-écriture [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Retour :**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture-écriture [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Valeur de transition du diaporama. Lecture-seule [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Retour :**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

Type de transition. Lecture-écriture [TransitionType](../../com.aspose.slides/transitiontype).

**Retour :**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Type de transition. Lecture-écriture [TransitionType](../../com.aspose.slides/transitiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Spécifie si ce son est un son intégré ou non. Si cet attribut est défini sur true, l'application générante est alertée pour vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon les besoins. Lecture-écriture booléen.

**Retour :**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Spécifie si ce son est un son intégré ou non. Si cet attribut est défini sur true, l'application générante est alertée pour vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon les besoins. Lecture-écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Spécifie un nom lisible par l'homme pour le son de la transition. La propriété (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) doit être assignée pour obtenir ou définir le nom du son. Lecture-écriture String.

**Retour :**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Spécifie un nom lisible par l'homme pour le son de la transition. La propriété \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) doit être assignée pour obtenir ou définir le nom du son. Lecture-écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture-écriture int.

--------------------

Correspond au attribut p14:dur de l'élément p:transition du schéma PresentationML. S'il n'est pas défini, la durée est déterminée automatiquement en fonction de la propriété \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) et du type de transition.

**Retour :**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture-écriture int.

--------------------

Correspond au attribut p14:dur de l'élément p:transition du schéma PresentationML. S'il n'est pas défini, la durée est déterminée automatiquement en fonction de la propriété \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) et du type de transition.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |