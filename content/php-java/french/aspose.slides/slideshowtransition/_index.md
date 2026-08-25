---
title: SlideShowTransition
second_title: Aspose.Sildes pour PHP via la Référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/slideshowtransition/
---
## SlideShowTransition classe

 Représente la transition du diaporama.
 
### equals {#equals}

| Nom | Description |
| --- | --- |
| equals (Object) | Détermine si les deux instances SlideShowTransition sont égales. Lecture/écriture boolean. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| obj | Object | Le SlideShowTransition à comparer avec le SlideShowTransition actuel. |

 **Retour:**
boolean


---


### getAdvanceAfter {#getAdvanceAfter}

| Nom | Description |
| --- | --- |
| getAdvanceAfter () | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### getAdvanceAfterTime {#getAdvanceAfterTime}

| Nom | Description |
| --- | --- |
| getAdvanceAfterTime () | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. Ce réglage peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, il est alors supposé qu'aucune avance automatique ne se produira. Lecture/écriture long. |

 **Retour:**
long


---


### getAdvanceOnClick {#getAdvanceOnClick}

| Nom | Description |
| --- | --- |
| getAdvanceOnClick () | Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est alors supposée. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### getDuration {#getDuration}

| Nom | Description |
| --- | --- |
| getDuration () | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture/écriture int. Correspond à l'attribut p14:dur de l'élément p:transition dans le schéma PresentationML. Si non défini, la durée est déterminée automatiquement en fonction de la propriété #getSpeed/ #setSpeed(int) et du type de transition. |

 **Retour:**
int


---


### getSound {#getSound}

| Nom | Description |
| --- | --- |
| getSound () | Renvoie ou définit les données audio intégrées. Lecture/écriture IAudio. |

 **Retour:**
[Audio](../audio)


---


### getSoundIsBuiltIn {#getSoundIsBuiltIn}

| Nom | Description |
| --- | --- |
| getSoundIsBuiltIn () | Spécifie si ce son est ou non un son intégré. Si cet attribut est défini sur true, l'application génératrice est avertie de vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon les besoins. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### getSoundLoop {#getSoundLoop}

| Nom | Description |
| --- | --- |
| getSoundLoop () | Cet attribut spécifie si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. Lecture/écriture boolean. |

 **Retour:**
boolean


---


### getSoundMode {#getSoundMode}

| Nom | Description |
| --- | --- |
| getSoundMode () | Définit ou renvoie le mode son pour la transition de la diapositive. Lecture/écriture TransitionSoundMode. |

 **Retour:**
int


---


### getSoundName {#getSoundName}

| Nom | Description |
| --- | --- |
| getSoundName () | Spécifie un nom lisible par l'homme pour le son de la transition. La propriété Sound( #getSound/ #setSound(IAudio)) doit être affectée pour obtenir ou définir le nom du son. Lecture/écriture String. |

 **Retour:**
String

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxException | Lorsque la propriété {@code Sound}( #getSound/ #setSound(IAudio)) n'est pas affectée. Ce nom apparaît dans l'interface utilisateur PowerPoint lors de la configuration manuelle du son de transition. |


---


### getSpeed {#getSpeed}

| Nom | Description |
| --- | --- |
| getSpeed () | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture/écriture TransitionSpeed. |

 **Retour:**
int


---


### getType {#getType}

| Nom | Description |
| --- | --- |
| getType () | Type de transition. Lecture/écriture TransitionType. |

 **Retour:**
int


---


### getValue {#getValue}

| Nom | Description |
| --- | --- |
| getValue () | Valeur de transition du diaporama. Lecture seule ITransitionValueBase. |

 **Retour:**
[OrientationTransition](../orientationtransition), [OptionalBlackTransition](../optionalblacktransition), [FlyThroughTransition](../flythroughtransition), [LeftRightDirectionTransition](../leftrightdirectiontransition), [TransitionValueBase](../transitionvaluebase), [EightDirectionTransition](../eightdirectiontransition), [EmptyTransition](../emptytransition), [RippleTransition](../rippletransition), [WheelTransition](../wheeltransition), [RevealTransition](../revealtransition), [MorphTransition](../morphtransition), [SplitTransition](../splittransition), [InOutTransition](../inouttransition), [GlitterTransition](../glittertransition), [SideDirectionTransition](../sidedirectiontransition), [ShredTransition](../shredtransition), [CornerDirectionTransition](../cornerdirectiontransition)


---


### hashCode {#hashCode}

| Nom | Description |
| --- | --- |
| hashCode () | Fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données telles qu'une table de hachage. |

 **Retour:**
int


---


### setAdvanceAfter {#setAdvanceAfter}

| Nom | Description |
| --- | --- |
| setAdvanceAfter (boolean) | Cet attribut spécifie si le diaporama passera à la diapositive suivante après un certain temps. Lecture/écriture boolean. |

 **Retour:**
void


---


### setAdvanceAfterTime {#setAdvanceAfterTime}

| Nom | Description |
| --- | --- |
| setAdvanceAfterTime (long) | Spécifie le temps, en millisecondes, après lequel la transition doit démarrer. Ce réglage peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, il est alors supposé qu'aucune avance automatique ne se produira. Lecture/écriture long. |

 **Retour:**
void


---


### setAdvanceOnClick {#setAdvanceOnClick}

| Nom | Description |
| --- | --- |
| setAdvanceOnClick (boolean) | Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est alors supposée. Lecture/écriture boolean. |

 **Retour:**
void


---


### setDuration {#setDuration}

| Nom | Description |
| --- | --- |
| setDuration (int) | Obtient ou définit la durée de l'effet de transition de la diapositive en millisecondes. Lecture/écriture int. Correspond à l'attribut p14:dur de l'élément p:transition dans le schéma PresentationML. Si non défini, la durée est déterminée automatiquement en fonction de la propriété #getSpeed/ #setSpeed(int) et du type de transition. |

 **Retour:**
void


---


### setSound {#setSound}

| Nom | Description |
| --- | --- |
| setSound ([Audio](../audio)) | Renvoie ou définit les données audio intégrées. Lecture/écriture IAudio. |

 **Retour:**
void


---


### setSoundIsBuiltIn {#setSoundIsBuiltIn}

| Nom | Description |
| --- | --- |
| setSoundIsBuiltIn (boolean) | Spécifie si ce son est ou non un son intégré. Si cet attribut est défini sur true, l'application génératrice est avertie de vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface utilisateur selon les besoins. Lecture/écriture boolean. |

 **Retour:**
void


---


### setSoundLoop {#setSoundLoop}

| Nom | Description |
| --- | --- |
| setSoundLoop (boolean) | Cet attribut spécifie si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama. Lecture/écriture boolean. |

 **Retour:**
void


---


### setSoundMode {#setSoundMode}

| Nom | Description |
| --- | --- |
| setSoundMode (int) | Définit ou renvoie le mode son pour la transition de la diapositive. Lecture/écriture TransitionSoundMode. |

 **Retour:**
void


---


### setSoundName {#setSoundName}

| Nom | Description |
| --- | --- |
| setSoundName (String) | Spécifie un nom lisible par l'homme pour le son de la transition. La propriété Sound( #getSound/ #setSound(IAudio)) doit être affectée pour obtenir ou définir le nom du son. Lecture/écriture String. |

 **Retour:**
void

 **Exception**

| Erreur | Condition |
| --- | --- |
| PptxException | Lorsque la propriété {@code Sound}( #getSound/ #setSound(IAudio)) n'est pas affectée. Ce nom apparaît dans l'interface utilisateur PowerPoint lors de la configuration manuelle du son de transition. |


---


### setSpeed {#setSpeed}

| Nom | Description |
| --- | --- |
| setSpeed (int) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante. Lecture/écriture TransitionSpeed. |

 **Retour:**
void


---


### setType {#setType}

| Nom | Description |
| --- | --- |
| setType (int) | Type de transition. Lecture/écriture TransitionType. |

 **Retour:**
void


---